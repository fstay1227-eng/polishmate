# Bubblewrap을 이용해 APK 만들기

## 1. Bubblewrap 설치
```bash
npm install -g @bubblewrap/cli
```

## 2. 초기화
```bash
bubblewrap init --manifest=https://YOUR_DOMAIN/manifest.json
```

## 3. 빌드
```bash
bubblewrap build
```

## 4. 설치
```bash
adb install output/PolishMate.apk
```
