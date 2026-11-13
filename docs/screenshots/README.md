# 스크린샷 목록

| 파일 | 내용 |
|---|---|
| 01_wsl-install-stuck-0percent.png | `wsl --install` 실행 후 0.0%에서 멈춤 (트러블슈팅 #2) |
| 02_wsl-web-download-ubuntu-0percent.png | `--web-download`로 WSL 설치 성공, Ubuntu 설치 0%에서 멈춤 |
| 03_vmp-enabled-reboot-required.png | VirtualMachinePlatform 활성화 100%, 재부팅 필요 |
| 04_reboot-not-applied.png | 재부팅이 적용되지 않아 같은 메시지 반복 |
| 05_ubuntu-installed-create-user.png | 재부팅 후 Ubuntu 설치 완료, 사용자 계정 생성 단계 |
| 06_ubuntu-user-admin-exists-error.png | `admin` 사용자명 생성 실패 (그룹 이름 중복) |
| 07_ubuntu-user-created.png | `suji` 계정 생성 및 비밀번호 설정 성공 |
| 08_ubuntu-prompt.png | Ubuntu 프롬프트 진입 |
| 09_docker-installer-file-in-use.png | Docker 설치 파일 "다른 응용 프로그램에서 사용 중" 오류 |
| 10_docker-install-config-wsl2.png | Docker Desktop 설치 옵션 (Per-user, WSL 2) |
| 11_docker-wsl-integration.png | Docker Desktop WSL integration에 Ubuntu 연결 |
| 12_docker-info-permission-denied.png | `docker info` 권한 오류 (트러블슈팅 #3) |
| 13_docker-info-success.png | 터미널 재실행 후 `docker info` 정상 출력 |
| 14_git-config-list.png | Git 사용자 정보·기본 브랜치 설정 및 `git config --list` |
| 15_git-clone.png | 저장소 clone 및 `ls -a` |
| 16_terminal-pwd-ls-mkdir-cd.png | `pwd`, `ls -la`, `mkdir`, `cd` 실습 |
| 17_terminal-file-ops.png | `touch`, `echo`, `cat`, `cp`, `mv`, `rm` 실습 |
| 18_chmod-file-dir-before-after.png | 파일(644→755)·폴더(755→700) 권한 변경 전/후 |
| 19_docker-hello-world.png | `docker run hello-world` 성공, `docker ps -a` |
| 20_docker-images-ubuntu-container.png | `docker images`, ubuntu 컨테이너 진입 후 `ls`·`echo`·`exit` |
| 21_docker-cmd-inside-container-error.png | 컨테이너 안에서 docker 명령 실행 → `command not found` (트러블슈팅 #4) |
| 22_docker-exec-vs-attach.png | exec 후 exit → Up 유지 / attach 후 exit → Exited |
| 23_docker-logs-start-stats-stop.png | `docker logs`, `start`, `stats --no-stream`, `stop` |
| 24_nano-filename-mistake.png | nano 저장 시 파일명이 `cat index.html`로 저장됨 (트러블슈팅 #5) |
| 25_dockerfile-nano.png | nano로 Dockerfile 직접 작성 |
| 26_docker-build-run-ps.png | `docker build -t my-web:1.0 .`, `docker run -p 8080:80`, `docker ps` |
| 27_curl-localhost-8080.png | `curl localhost:8080` 응답 확인 |
| 28_browser-localhost-8080.png | 브라우저 `localhost:8080` 접속 화면 (주소창 포함, 북마크바 제거) |
| 29_bind-mount-after-and-volume-persistence.png | 바인드 마운트 호스트 수정 후 반영 확인 + 볼륨 생성·연결·컨테이너 삭제 후 데이터 유지 |
