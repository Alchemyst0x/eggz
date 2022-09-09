# This repo is just a quick-save and drop off for information relating to ...

```
0xdb8592dc3780c3fab55e3709f32dd7efa9f5b1a8ed94d8a00c761293b4409caf
```

... the above-written contract. Seen here on [Etherscan](https://etherscan.io/address/0x8b0e42f366ba502d787bb134478adfae966c8798#code)

## Stego-stuff (stegonography)

- [ ] [StegOnline](https://stegonline.georgeom.net/upload) - upload a file and see if it contains any hidden data
- [ ] [StegCracker](https://futureboy.us/stegano/decinput.html) - upload a file and see if it contains any hidden data
- [ ] [Aperi'Solve](https://www.aperisolve.com/) - upload a file and it will analyze it with a crapload of commono stego tools

### Images tested thus far:

Image1: [00000001.jpg](./img/00000001.jpg)

Relevant analysis: [https://www.aperisolve.com/bb44b8fefc2de231fc5d3082bccf1532](https://www.aperisolve.com/bb44b8fefc2de231fc5d3082bccf1532)

Interesting findings:

```
b1,rgba,lsb,xy .. text: ["U" repeated 11 times]
b1,abgr,msb,xy .. text: ["U" repeated 11 times]
b2,r,lsb,xy .. text: "UUjUUUjU@U:"
b2,g,lsb,xy .. text: "UUUUUUUUUj"
b2,g,msb,xy .. text: ["U" repeated 8 times]
b2,b,lsb,xy .. text: "UUjUUUjU@"
b2,rgba,lsb,xy .. text: ";;wwwwww"
b2,abgr,msb,xy .. text: ["w" repeated 8 times]
b3,rgba,lsb,xy .. text: "VugVugVugz"
b4,r,lsb,xy .. text: ["w" repeated 10 times]
b4,r,msb,xy .. text: "333UUUUUUUU"
b4,g,lsb,xy .. text: "DUUUfffwwww"
b4,g,msb,xy .. text: ["D" repeated 10 times]
b4,b,lsb,xy .. text: "\"\"\"\"33\"\""
b4,b,msb,xy .. text: ["w" repeated 11 times]
b4,abgr,msb,xy .. text: "?Z?Z?Z?Z?Z?Z"
```

Image2: [00000002.jpg](./img/00000002.jpg)

Relevant analysis: [https://www.aperisolve.com/b4752b5b3f04bf68543e1f6215432287](https://www.aperisolve.com/b4752b5b3f04bf68543e1f6215432287)