# Recorder
### 녹음기 앱

#### 음성을 녹음하고, 녹음한 음성을 재생하는 기본적인 녹음기 기능을 구현한 앱 입니다.
### Blog
* <https://hwayomingdlog.tistory.com/221>
* <https://hwayomingdlog.tistory.com/222>
* <https://hwayomingdlog.tistory.com/223>
</br>

## 주 기능
### Record 녹음하기
* 🔴 버튼을 클릭하여 음성 녹음을 시작하고 ◼ 버튼을 클릭해서 녹음을 종료할 수 있습니다.
* Visualization하여 음성의 진폭에 따라 변화하는 UI를 확인할 수 있습니다.

### Play 재생하기
* ▶ 버튼을 클릭해서 녹음한 음성을 재생하고 ◼ 버튼을 클릭해서 종료할 수 있습니다.
* 녹음 시 Visualization한 진폭의 변화도 함께 재생 됩니다.
</br>

## 활용 기술
* ConstraintLayout - ConstraintLayout의 Chain을 이용하여 View들의 위치를 설정하였습니다.
* Custom View - 진폭의 변화에 따라 선을 그리기 위해 커스텀 뷰 SoundVisualizerView를 만들어 Paint와 Canvas 객체를 활용하고 invalidate() 함수 호출을 통해 특정 간격마다 OnDraw() 콜백 메서드가 호출되도록 하였습니다.
* MediaRecorder, MediaPlayer - 녹음 기능과 재생 기능을 위해 MediaRecorder과 MediaPlayer를 사용하고 State에 따른 로직을 적용했습니다.
</br>

***
<img src="/img/img0.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img1.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img2.png" width="300px" height="600px" title="" alt=""></img>
