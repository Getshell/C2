# 《C2：下一代RAT》

本项目用来收集整理C2工具的相关内容，包括优秀的C2工具或优秀的思路等。远控是一门古老的技术，C2是一门新兴的艺术！不想拿到控制权限的黑客不是好黑客。

本项目创建于2021年8月19日，最近的一次更新时间为2022年1月5日。

- [0x01-C2资源]()
- [0x02-C2工具]()
- [0x03-C2免杀]()
- [0x04-C2开发]()
- [0x05-C2未来]()

## 0x01-C2资源

- https://github.com/tcostam/awesome-command-control
- https://github.com/Ignitetechnologies/Command-Control

一、基础书籍

二、视频资源
- [ ] https://www.youtube.com/watch?v=eTA7weRp2yk

三、其他资源
- [ ] https://github.com/ProfessionallyEvil/C4
- [ ] https://github.com/JAYMONSECURITY/JMSec-Agent-RTO
- [ ] https://github.com/timb-machine/linux-malware

九、思考备注

- C2是什么？远控是什么？流量隧道是什么？C2=远控+流量隧道？
- 优秀的C2是什么？
- Webshell管理工具算不算C2？可以执行命令的就算？

## 0x02-C2工具

- https://github.com/topics/c2
- https://github.com/search?q=Command+and+Control
- https://github.com/topics/command-and-control
- https://github.com/search?q=C2+frameworks
- https://github.com/topics/rat
- https://github.com/search?q=RAT
- https://github.com/alphaSeclab/awesome-rat

一、优秀工具
- [ ] https://github.com/Cobalt-Strike
- [ ] https://github.com/rapid7/metasploit-framework
- [ ] https://github.com/FunnyWolf/Viper
- [ ] https://github.com/0x727/MetasploitCoop_0x727
- [ ] https://github.com/FlyfishSec/rsGen

二、Go开发
- [x] https://github.com/TerminalJockey/Kudzu
- [x] https://github.com/njcx/gocmd
- [ ] https://github.com/Ne0nd0g/merlin
- [ ] https://github.com/Ne0nd0g/merlin-agent
- [ ] https://github.com/EngineerBetter/control-tower
- [ ] https://github.com/activecm/rita
- [ ] https://github.com/DeimosC2/DeimosC2
- [ ] https://github.com/Tylous/SourcePoint
- [ ] https://github.com/iimrudy/PrismaController
- [ ] https://github.com/timwhitez/Doge-Persistence-Platform
- [ ] https://github.com/mthbernardes/GTRS
- [ ] https://github.com/tiagorlampert/CHAOS
- [ ] https://github.com/sensepost/goDoH
- [ ] https://github.com/BishopFox/sliver
- [ ] https://github.com/cyberark/kubesploit
- [ ] https://github.com/lu4p/ToRat
- [ ] https://github.com/KCarretto/paragon
- [ ] https://github.com/lu4p/ToRat_server
- [ ] https://github.com/degenerat3/meteor
- [ ] https://github.com/angus-y/PyIris-backdoor
- [ ] https://github.com/aminaxx/bossbash
- [ ] https://github.com/geemion/Khepri
- [ ] https://github.com/elleven11/pantegana
- [ ] https://github.com/maxlandon/wiregost
- [ ] https://github.com/CMatri/MeetC2
- [ ] https://github.com/phil-fly/generate
- [ ] https://github.com/msoap/shell2http
- [ ] https://github.com/Maka8ka/NGLite
- [ ] https://github.com/veo/vshell
- [ ] https://github.com/kgretzky/evilginx2
- [ ] https://github.com/EkiXu/reverse-shell-manager
- [ ] https://github.com/looCiprian/GC2-sheet
- [ ] https://github.com/whitehatnote/BlueShell
- [ ] https://github.com/Binject/shellcode
- [ ] https://github.com/sairson/SecShell
- [ ] https://github.com/fcre1938/Ortau
- [ ] https://github.com/jm33-m0/emp3r0r
- [ ] https://github.com/ssut/payload-dumper-go
- [ ] https://github.com/webxscan/linux_rat

三、Python开发
- [ ] https://github.com/its-a-feature/Mythic
- [ ] https://github.com/p3nt4/Nuages
- [ ] https://github.com/Arno0x/WSC2
- [ ] https://github.com/r00t-3xp10it/venom
- [ ] https://github.com/Coalfire-Research/Slackor
- [ ] https://github.com/maldevel/canisrufus
- [ ] https://github.com/Ziconius/FudgeC2
- [ ] https://github.com/0x09AL/DNS-Persist
- [ ] https://github.com/byt3bl33d3r/SILENTTRINITY
- [ ] https://github.com/UnkL4b/BabyShark
- [ ] https://github.com/th3r4ven/Bifrost
- [ ] https://github.com/0xGhazy/F4T3H-WinC2
- [ ] https://github.com/m8r0wn/transportc2
- [ ] https://github.com/mitre/caldera
- [ ] https://github.com/h0mbre/Dali
- [ ] https://github.com/byt3bl33d3r/SILENTTRINITY
- [ ] https://github.com/Telefonica/ibombshell
- [ ] https://github.com/zerosum0x0/koadic
- [ ] https://github.com/Marten4n6/EvilOSX
- [ ] https://github.com/mhaskar/Octopus
- [ ] https://github.com/AdrianVollmer/PowerHub
- [ ] https://github.com/slyd0g/SK8PARK
- [ ] https://github.com/trustedsec/trevorc2
- [ ] https://github.com/n1nj4sec/pupy
- [ ] https://github.com/neoneggplant/EggShell
- [ ] https://github.com/nil0x42/phpsploit
- [ ] https://github.com/loseys/BlackMamba
- [ ] https://github.com/Coalfire-Research/Slackor
- [ ] https://github.com/daanzu/kaldi-active-grammar
- [ ] https://github.com/KCarretto/Arsenal
- [ ] https://github.com/PushpenderIndia/nekros
- [ ] https://github.com/MythicAgents/venus
- [ ] https://github.com/tanc7/dark-lord-obama
- [ ] https://github.com/MythicAgents/Medusa
- [ ] https://github.com/MythicAgents/merlin
- [ ] https://github.com/MythicAgents/venus
- [ ] https://github.com/NullCode13/NullRAT
- [ ] https://github.com/Ba-hub/GhostRat
- [ ] https://github.com/pucarasec/zuthaka
- [ ] https://github.com/Cr4sh/MicroBackdoor
- [ ] https://github.com/gl4ssesbo1/Nebula
- [ ] https://github.com/reveng007/C2_Server
- [ ] https://github.com/alysif/SimpleRAT
- [ ] https://github.com/bigb0sss/kurosaki-C2
- [ ] https://github.com/FortyNorthSecurity/C2concealer
- [ ] https://github.com/Ph3nX-Z/WebShell-C2
- [ ] https://github.com/Rvn0xsy/Linco2
- [ ] https://github.com/mycve/WinController
- [ ] https://github.com/t3hbb/NSGenCS
- [ ] https://github.com/wavestone-cdt/abaddon
- [ ] https://github.com/hash3liZer/SillyRAT
- [ ] https://github.com/lapolis/palinka_c2
- [ ] https://github.com/mycve/TerminalController
- [ ] https://github.com/nathanlopez/Stitch
- [ ] https://github.com/5alt/ZeroRAT

四、Java开发
- [ ] https://github.com/LSTS/neptus
- [ ] https://github.com/Ramos-dev/OSSTunnel

五、C#开发
- [ ] https://github.com/SharpC2/SharpC2
- [ ] https://github.com/sf197/Telegra_Csharp_C2
- [ ] https://github.com/NYAN-x-CAT/AsyncRAT-C-Sharp
- [ ] https://github.com/cobbr/Covenant
- [ ] https://github.com/onSec-fr/Http-Asynchronous-Reverse-Shell
- [ ] https://github.com/quasar/Quasar
- [ ] https://github.com/fozavci/petaqc2
- [ ] https://github.com/Raffy27/OrionPanel
- [ ] https://github.com/uvzz/IERat
- [ ] https://github.com/qwqdanchun/DcRat
- [ ] https://github.com/ryhanson/ExternalC2
- [ ] https://github.com/sogonsec/ViolentFungus-C2
- [ ] https://github.com/xdnice/PCShare
- [ ] https://github.com/sysrom/DcRatCHS
- [ ] https://github.com/A-D-Team/SharpMemshell
- [ ] https://github.com/void-stack/Orcus-1.9.1-src
- [ ] https://github.com/FULLSHADE/WARFOX-C2

六、C++开发
- [ ] https://github.com/FSecureLABS/C3
- [ ] https://github.com/monoxgas/FlyingAFalseFlag
- [ ] https://github.com/SafeBreach-Labs/pinjectra
- [ ] https://github.com/bats3c/shad0w
- [ ] https://github.com/iagox86/dnscat2
- [ ] https://github.com/bigBestWay/dnstunnel
- [ ] https://github.com/pwn1sher/uuid-loader

七、Rust开发
- [ ] https://github.com/postrequest/link

八、PHP开发
- [ ] https://github.com/EnginDemirbilek/NorthStarC2

九、Powershell开发
- [ ] https://github.com/ahmedkhlief/Ninja
- [ ] https://github.com/BC-SECURITY/Empire
- [ ] https://github.com/nettitude/PoshC2
- [ ] https://github.com/r00t-3xp10it/meterpeter
- [ ] https://github.com/xRET2pwn/PickleC2
- [ ] https://github.com/alexfrancow/badusb_botnet
- [ ] https://github.com/Raffy27/OrionServer

十、其他语言
- [ ] https://github.com/Project-Prismatica/Prismatica
- [ ] https://github.com/jephthai/EvilVM
- [ ] https://github.com/KINGSABRI/chkdfront
- [ ] https://github.com/Raffy27/OrionBot
- [ ] https://github.com/MisterTea/EternalTerminal
- [ ] https://github.com/sneakerhax/C2PE
- [ ] https://github.com/0x727/SchTask_0x727
- [ ] https://github.com/enkomio/AlanFramework
- [ ] https://github.com/preludeorg/community
- [ ] https://github.com/Arno0x/DBC2

## 0x03-C2免杀

## 0x04-C2开发

## 0x05-C2未来

## 0x06-C2参考

- https://thestack.technology/from-c2-to-c3
- https://www.foregenix.com/blog/a-first-look-at-todays-command-and-control-frameworks
- https://www.thec2matrix.com
- http://ask.thec2matrix.com
- https://threatexpress.com/blogs/2019/c2-agent-comparison
- https://www.varonis.com/blog/what-is-c2
- https://www.thec2matrix.com/matrix
- https://docs.google.com/spreadsheets/d/1b4mUxa6cDQuTV2BPC6aA-GR4zGZi0ooPYtBe4IgPsSc/edit#gid=0
- https://awesomeopensource.com/projects/c2

