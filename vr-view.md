# [VR View](https://developers.google.com/vr/concepts/vrview)
VR View는 당신이 데스크탑, 모바일, 안드로이드 네이티브, iOS 네이티브 어디에나 360도 미디어를 삽입할 수 있게 해줍니다.
<br>

### 제약 사항
Native
- iOS 8 and higher.
- Android 4.4 (Kit Kat) and higher.

Web
- Modern versions of Chrome and Opera on Windows, macOS, Linux, Android, and iOS.
- Modern versions of Safari on macOS and iOS.
- Modern versions of Firefox on Windows, macOS, and Linux.
- Modern versions of IE 11 and Edge on Windows.
<br>

### 이미지 사양
- [equirectangular-panoramic](https://en.wikipedia.org/wiki/Equirectangular_projection) 포맷으로 된 이미지가 필요합니다.
- VR 이미지는 png, jpg, gif 등으로 저장되어야 합니다. jpg를 추천합니다. 
- 좋은 퍼포먼스를 위해 2048 또는 4096 사이지를 권장합니다.
- Mono images should be 2:1 aspect ratio (e.g. 4096 x 2048).
- Stereo images should be 1:1 aspect ratio (e.g. 4096 x 4096).
<br>

### 비디오 사양
- [equirectangular-panoramic](https://en.wikipedia.org/wiki/Equirectangular_projection) 포맷으로 된 비디오가 필요합니다.
- VR 비디오는 h264로 인코딩된 mp4로 저장되어야 합니다.
- Mono videos should be 2:1 aspect ratio.
- Stereo videos should be 1:1 aspect ratio.
- Some older devices cannot decode video larger than 1080p (1920x1080). If maximum compatibility and quality is a priority, we - recommend that users provide both a monoscopic 1920x1080 video and a stereo video at 2048x2048 or higher.
<br>

### 실세계 캡처
[구글 카드보드 카메라 앱](https://play.google.com/store/apps/details?id=com.google.vr.cyclops&hl=en)을 사용하거나 [Ricoh Theta 360 카메라](https://theta360.com/ko/)를 사용합니다.
<br>

### 3D세계 캡처
유니티 언리얼 등
<br>
<br>


# [VR View 샘플코드](https://developers.google.com/vr/android/samples/vrview)
### [샘플 다운로드](https://developers.google.com/vr/android/download)
### [Getting Started](https://developers.google.com/vr/android/get-started#start_your_own_project)
웹에서 돌려보기 : http://storage.googleapis.com/vrview/index.html?image=//<http:// 뺀 이미지 URL>

