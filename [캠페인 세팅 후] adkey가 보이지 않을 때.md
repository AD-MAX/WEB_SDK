# 테스트 캠페인 세팅 후 <br> 테스트 과정에서 vegas_adkey={adkey} 가 보이지 않을 때
<br>

이런 경우에는 **리다이렉트**를 하고 있어서 발생합니다.

### 1. 리다이렉트 문제
<br>
광고주의 사이트에서 여러 이유에 의해서 redirect를 해서 애드맥스에게 제공한 랜딩url이 다른 페이지로 또 다시 rediect하면 <br>
vegas_adkey={adkey} 값이 url에 보이지 않습니다.

 vegas_adkey={adkey}은 광고주의 개발자분이 최종 landing 페이지까지(애드맥스의 a 스크립트가 심어있는) url로<br>
 vegas_adkey={adkey} 파라미터와 값을 전달해주셔야 합니다.
<br><br><br><br>

