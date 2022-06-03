# rg 13 times out but rg 12 works fine
```
git clone https://github.com/sc-voice/rg-bug
cd rg-bug
npm install
```

### Test with rg 12 (HAPPY!)

All tests pass
```
scripts/install-ripgrep 12.1.1
npm run test
```

### Test with rg 13 (SAD!)
Second test times out

```
scripts/install-ripgrep 13.0.0
npm run test
```

