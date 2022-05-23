#이미지의 표현과 동영상, 음악 등 멀티미디어를 지원하는 태그

<hr>

# 1. 이미지
### 웹페이지에 이미지를 삽입하는 경우, img tag를 사용한다.

<table>
    <tr>
        <th>attribute</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>src</td>
        <td>이미지 파일 경로</td>
    </tr>
    <tr>
        <td>alt</td>
        <td>이미지 파일이 없을 경우 표시되는 문장</td>
    </tr>
    <tr>
        <td>width</td>
        <td>이미지의 너비(CSS에서 지정하는 것이 일반적)</td>
    </tr>
    <tr>
        <td>height</td>
        <td>이미지의 높이(CSS에서 지정하는 것이 일반적)</td>
    </tr>
</table>

```angular2html
<!DOCTYPE html>
<html>
  <body>
    <img src="assets/images/doug.jpg" alt="doug" width="100">
    <img src="assets/images/wrongname.gif" alt="이미지가 없습니다.">
  </body>
</html>
```

<!DOCTYPE html>
<html>
  <body>
    <img src="https://poiemaweb.com/assets/images/doug.jpg" alt="doug" width="100">
    <img src="assets/images/wrongname.gif" alt="이미지가 없습니다.">
  </body>
</html>

<hr>

# 2. 미디어

## 2.1 audio

### audio 태그는 HTML5에서 새롭게 추가된 태그이다. IE8 이하에서는 사용할 수 없다.


<table>
    <tr>
        <th>attribute</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>src</td>
        <td>음악 파일 경로</td>
    </tr>
    <tr>
        <td>preload</td>
        <td>재생 전에 음악 파일을 모두 불러올 것인지 지정</td>
    </tr>
    <tr>
        <td>autoplay</td>
        <td>음악 파일을 자동의 재생 개시할 것인지 지정</td>
    </tr>
    <tr>
        <td>loop</td>
        <td>음악을 반복할 것인지 지정</td>
    </tr>
    <tr>
        <td>controls</td>
        <td>음악 재생 도구를 표시할 것인지 지정. 재생 도구의 외관은 브라우저마다 차이가 있다.</td>
    </tr>
</table>

```angular2html
<!DOCTYPE html>
<html>
  <body>
    <audio src="assets/audio/Kalimba.mp3" controls></audio>
  </body>
</html>
```
<!DOCTYPE html>
<html>
  <body>
    <audio src="assets/audio/Kalimba.mp3" controls></audio>
  </body>
</html>

### 웹브라우저 별로 지원하는 음악 파일 형식이 다르다. 파일 형식에 따라 재생되지 않는 브라우저가 존재한다는 뜻이다.

<table>
    <tr>
        <th>Browser</th>
        <th>MP3</th>
        <th>Wav</th>
        <th>Ogg</th>
    </tr>
    <tr>
        <td>Internet Explorer</td>
        <td>YES</td>
        <td>NO</td>
        <td>NO</td>
    </tr>
    <tr>
        <td>Chrome</td>
        <td>YES</td>
        <td>YES</td>
        <td>YES</td>
    </tr>
    <tr>
        <td>Firefox</td>
        <td>YES(24~)</td>
        <td>YES</td>
        <td>YES</td>
    </tr>
    <tr>
        <td>Safari</td>
        <td>YES</td>
        <td>YES</td>
        <td>NO</td>
    </tr>
    <tr>
        <td>Opera</td>
        <td>YES(25~)</td>
        <td>YES</td>
        <td>YES</td>
    </tr>
</table>

### source 태그를 사용하여 파일 형식의 차이 문제를 해결 할 수 있다. type 어트리뷰트는 생략 가능하다.

```angular2html
<!DOCTYPE html>
<html>
  <body>
    <audio controls>
      <source src="assets/audio/Kalimba.mp3" type="audio/mpeg">
      <source src="assets/audio/Kalimba.ogg" type="audio/ogg">
    </audio>
  </body>
</html>
```
<!DOCTYPE html>
<html>
  <body>
    <audio controls>
      <source src="assets/audio/Kalimba.mp3" type="audio/mpeg">
      <source src="assets/audio/Kalimba.ogg" type="audio/ogg">
    </audio>
  </body>
</html>

## 2.2 비디오

### video 태그는 HTML5에서 새롭게 추가된 태그이다. IE8 이하에서는 사용할 수 없다.


<table>
    <tr>
        <th>attribute</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>scr</td>
        <td>동영상 파일 경로</td>
    </tr>
    <tr>
        <td>poster</td>
        <td>동영상 준비 중에 표시될 이미지 파일 경로</td>
    </tr>
    <tr>
        <td>preload</td>
        <td>재생 전에 동영상 파일을 모두 불러올 것인지 지정</td>
    </tr>
    <tr>
        <td>autoplay</td>
        <td>동영상 파일을 자동의 재생 개시할 것인지 지정</td>
    </tr>
    <tr>
        <td>loop</td>
        <td>동영상을 반복할 것인지 지정</td>
    </tr>
    <tr>
        <td>controls</td>
        <td>동영상 재생 도구를 표시할 것인지 지정. 재생 도구의 외관은 브라우저마다 차이가 있다.</td>
    </tr>
    <tr>
        <td>width</td>
        <td>동영상의 너비를 지정</td>
    </tr>
    <tr>
        <td>height</td>
        <td>동영상의 높이를 지정</td>
    </tr>
</table>

### audio 태그와 마찬가지로 파일 형식의 차이 문제가 발생할 수 있다. source 태그를 사용하여 형식 차이 문제를 해결한다. type 어트리뷰트는 생략 가능하다.

<table>
    <tr>
        <th>Browser</th>
        <th>MP4</th>
        <th>WebM</th>
        <th>Ogv</th>
    </tr>
    <tr>
        <td>Internet Explorer</td>
        <td>YES</td>
        <td>NO</td>
        <td>NO</td>
    </tr>
    <tr>
        <td>Chrome</td>
        <td>YES</td>
        <td>YES</td>
        <td>YES</td>
    </tr>
    <tr>
        <td>Firefox</td>
        <td>YES(21~)</td>
        <td>YES</td>
        <td>YES</td>
    </tr>
    <tr>
        <td>Safari</td>
        <td>YES</td>
        <td>NO</td>
        <td>NO</td>
    </tr>
    <tr>
        <td>Opera</td>
        <td>YES(25~)</td>
        <td>YES</td>
        <td>YES</td>
    </tr>
</table>

```angular2html
<!DOCTYPE html>
<html>
  <body>
    <video width="640" height="360" controls>
      <source src="assets/video/wildlife.mp4" type="video/mp4">
      <source src="assets/video/wildlife.webm" type="video/webm">
    </video>
  </body>
</html>
```
<!DOCTYPE html>
<html>
  <body>
    <video width="640" height="360" controls>
      <source src="assets/video/wildlife.mp4" type="video/mp4">
      <source src="assets/video/wildlife.webm" type="video/webm">
    </video>
  </body>
</html>
