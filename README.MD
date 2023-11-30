간단하게 git clone 하고 아래의 명령어들 실행 (Windows)

`Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass`

'.\ESXi-Customizer-PS.ps1 -pkgDir ".\outputs" -vft -load cpu-microcode,net55-r8168,net51-r8169,net51-sky2,net-r8101,net-r8139too -v67'

추가로 설치할 드라이버는 콤마로 입력하면 됨.
