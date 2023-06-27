# 개발환경

XAMPP 버전 **5.5.38**

(xampp를 설치하고 난 후에 폴더명을 변경하게 되면 xampp-control-panel에서 apache start시킬 때 
 에러남. 폴더명을 xampp말고 다른걸로 바꾸고 싶으면 처음 설치할 때 바꾸거나 이미 xampp로 설치한 경우에는 
  파일을 삭제하고 다시 설치해야 함.)

처음 apache를 실행하면 80번 포트로 설정이 돼 있는데 포트번호를 변경하고 싶으면 

'xampp -> apache -> conf -> extra -> httpd-vhosts.conf',
'xampp -> apache -> conf -> httpd.conf' 

이 두 파일에서 원하는 포트 번호를 설정해줘야 함.



DB : MariaDB

DB관련 덤프 파일들을 phpMyAdmin에서 업로드 할때 업로드 가능한 파일 최대 크기 기본값이 2,000kb 정도 밖에 
안되기 때문에 'xampp -> php -> php.ini' 파일에서 'post_max_size'와 'upload_max_filesize'를 업로드 할
파일 사이즈에 알맞게 변경 해줘야 함.


