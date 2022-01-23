# Going_Deeper

## 준비물
아래와 같이 작업환경을 준비합시다.

  - $ mkdir -p ~/aiffel/face_detector/assets
  - $ mkdir -p ~/aiffel/face_detector/dataset
  - $ mkdir -p ~/aiffel/face_detector/checkpoints
WIDER FACE 데이터셋 홈페이지의 4개의 zip파일을 사용할 예정입니다. 사용할 WIDER_xxx.zip 파일들은 아래와 같이 구글드라이브에 올라가 있습니다.

다만 데이터는 이미 준비되어 있으니 다운로드할 필요는 없습니다.

- WIDER Face Training Images [Google Drive]
- WIDER Face Validation Images [Google Drive]
- WIDER Face Testing Images [Google Drive]
- Face annotations [WIDER FACE 데이터셋 홈페이지에서 다운로드할 수 있습니다.]
- 준비된 데이터를 연결만 해줍시다.

  - $ ln -s ~/data/* ~/aiffel/face_detector
  face_detector.zip
준비된 데이터에는 9개의 python 모듈 파일이 포함되어 있습니다.

위 face_detector.zip파일에 9개의 python 모듈이 압축되어 있으니 참고하세요.
