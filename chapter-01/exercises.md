# CHAPTER1. ANYTHING FROM ALMOST NOTHING

## Intermission: Equivalence Exercises

1. λxy.xz - answer: b - λmn.mz
2. λxy.xxy - answer: c - λa(λb.aab)
3. λxyz.zx - answer: b - λtos.st


## Chapter excercises

### Combinators?

1. λx.xxx - True
2. λxy.xz - False
3. λxyz.xy(zx) - True
4. λxyz.xy(zxy) - True
5. λxy.xy(zxy) - False

### Normal form or diverge?

1. λx.xxx - Normal
2. (λz.zz)(λy.yy) - Diverge
3. (λx.xxx)z - Normal

### Beta reduce

1. (λabc.cba)zz(λwv.w)
   (λa.λb.λc.cba)(z)z(λw.λv.w)
   (λb.λc.cbz)(z)(λw.λv.w)
   (λc.czz)(λw.λv.w)
   λw.λv.wzz
   λv.zz
   z
2. (λx.λy.xyy)(λa.a)b
   (λy.λa.ayy)b
   λa.abb
   bb

