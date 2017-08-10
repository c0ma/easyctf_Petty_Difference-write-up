Description:

Written by dududum561

I found two files in a secret room. They look like jumbled letters with no patterns. I mean look at it! file1 is identical to file2, right?

file1: https://pastebin.com/hJKVA9ZT

file2: https://pastebin.com/u0PXptYv

I wrote a small python script to compare the 2 files

```
f1 = open("file1","r").read()
f2 = open("file2","r").read()
out = ""

x=0
for y in f1:
        if f2[x] != y:
                out += y
        x+=1
print out
```

output: }4_gn1k00l_3r3w_u0y_3cn3r3ff1d_3ht_3b_y4m_s1ht{ftcysae

reverse the string

```
print out[::-1]
easyctf{th1s_m4y_b3_th3_d1ff3r3nc3_y0u_w3r3_l00k1ng_4}
```
