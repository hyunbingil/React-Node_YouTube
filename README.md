### 🎥 비디오 업로드 FORM
1. Upload Page 만들기
2. Upload Page Route 만들기
3. Upload Page Header Tab 만들기
4. Form Template 만들기
5. 파일을 올리는 Template 만들기 위해 Drop-zone 다운받기
```
npm install react-dropzone --save
```
> save를 해야 다운 받았다고 적혀진다.
6. onChange func 만들기

### 🎥 Multer로 서버에 비디오 저장하기
1. onDrop func 만들기
2. 노드 서버에 파일을 저장하기 위해 Ddependency를 먼저 다운로드
```
npm install multer --save
```
> server directory에
3. 비디오 파일을 서버로 보내기
4. 받은 비디오 파일을 서버에서 저장
5. 파일 저장 경로를 클라이언트로 전달해주기

### 🎥 ffmpeg로 비디오 썸네일 생성하기
1. 썸네일 생성을 위한 dependecy 다운 받기
```
ffmpeg 를 다운받는다.(구글)
```
```
npm install fluent-ffmpeg --save
```
2. 서버에 저장된 비디오를 이용한 썸네일 생성
3. 생성된 썸네일을 서버에 저장
4. 썸네일 이미지 파일 경로 정보를 클라이언트에 보내기
5. 썸네일 이미지를 화면에 표시