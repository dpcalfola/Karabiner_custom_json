# karabiner caps-lock 단축키 json

<hr>
<br>

## 사용 방법

> ~/.config/karabiner/assets/complex_modifications

위 경로의 폴더 안에 json 파일을 복사 붙여넣기 합니다.

혹은<br>
Karabiner-Elements 의 설정 메뉴 <br>

> Preferences > mice > Export & Import > Open config folder<br>

버튼을 누르면 설정 파일 경로로 쉽게 접근 가능합니다.

파일을 복사 붙여넣기 하였다면 Karabiner-Elements 의 설정 메뉴 <br>
Complex modifications > Add rule 창에서 "Fola custom" 이름의 룰을 설정, 추가 할 수 있습니다.

<hr>
<br>
<br>

## ver 2.3
* file name : 
* 
  * fola_custom_v2.3.json

* Shortcut:
  * caps + hjkl : 방향키
  * caps + n : backspace
  * caps + m : delete
  * caps + g : enter
  * caps + p : play or pause
* 변경사항:
  * 한영전환 단축키 삭제
    * 인풋랙 문제 해결이 되지 않아 한영전환 단축키를 제거하였습니다.
    * 한영전환은 해머스푼에서 단축키를 작성하여 사용하고 있습니다.
    * 해머스푼을 이용한 솔루션은 인풋랙이 전혀 없으며 편집도 손쉽게 가능합니다. 아래 링크를 참고하세요.
      * [Github > Fola's Hammerspoon config code](https://github.com/dpcalfola/hammerspoon_config)
  * 개인적 용도의 tm680 config data 삭제
  * Media controls 의 play_or_pose(Fn + F8) 단축키 추가:
    * caps + p : play or pause


<hr>
<br>
<br>

## ver 2.1
* file name : 
  * fola_custom_v2.1.json

* Shortcut:
  * caps + hjkl : 방향키
  * caps + space : 한영전환( 기본 한영전환을 ctrl + space 로 맞춰주셔야 동작합니다)
  * caps + n : backspace
  * caps + m : delete
  * caps + g : enter


* 변경사항
  * 한영전환 단축키 개선 (Issue - 인풋랙 존재)
    * caps + space : F19 (기본 한영전환을 F19로 맞추어 주세요)
    * 기존의 (ctrl + space) 조합키 보다 반응성이 더 좋습니다.   

<hr>
<br>






## 사용 및 수정 방법 안내

[블로그 - 카라비너(Karabiner-Elements) json 커스텀 키매핑](https://dpcalfola.tistory.com/entry/Karabiner-Elements-json-custom)


<hr>
<br>

### 수정, 재배포 자유
블로그나 깃허브로 출처를 남겨주시면 감사하겠습니다.
필수는 아닙니다.