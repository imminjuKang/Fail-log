# Web 문제 풀이 과정

### Ascii? Unicode?

<p align="center">
  <img src="https://github.com/user-attachments/assets/8e78b463-6734-4cc5-b263-fd4d994dc606" width="45%" style="margin-right:10px;"/>
  <img src="https://github.com/user-attachments/assets/1458ba20-b847-420d-a5aa-79a4be981cfc" width="45%"/>
</p>

- os.environ : 파이썬 코드에서 접근할 수 있는 환경변수 이름과 값이 딕셔너리 형태로 저장 (Flag가 저장되어 있는 방식)
- flag 도출 방법 : initial_host_length와 final_host_length가 다르면 flag 출력
- url 입력 -> 해당 url host length 계산 -> url 방문 후 final_url 생성 -> final_url의 host length 계산

  
<p align="center">
  <img src="https://github.com/user-attachments/assets/69cc54b2-4a7c-4bb9-a547-ec1aac0b1d76" width="45%" style="margin-right:10px;"/>
  <img src="https://github.com/user-attachments/assets/49ea31c5-49ee-4ee8-96c5-52a06d047f63" width="45%"/>
</p>

- urlparse() attribute: scheme(='https'), netloc(='www.'), path, params, query, fragment, username, password, hostname(hostname 혹은 ""), port
- root_domain의 길이를 return
- 같은 url에 접속하는데 hostname을 다르게 설정하는 방법 .. ?


---


### Flashum

<p align="center">
  <img src="https://github.com/user-attachments/assets/55f3ba09-f2c2-4a45-b0b3-d404e5793ec5" width="45%" style="margin-right:10px;"/>
  <img src="https://github.com/user-attachments/assets/d9d90496-60f2-4586-89f4-530c451b32d7" width="45%"/>
</p>

- flag 찾는 방법 : admin 관리자 권한으로 로그인 필요

<p align="center">
  <img width="1065" height="523" alt="image" src="https://github.com/user-attachments/assets/e0e6b6b8-e7ce-414a-a34f-db247ebf4949" />
</p>

- 인증 토큰 활용하기
- HttpOnly; Path=/ : 
