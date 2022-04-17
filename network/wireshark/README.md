# manual-wireshark

### 무료 프록시 서버
http://www.freeproxylists.net/  

### 윈도우 방화벽 설정
firewall.cpl  
아웃바운드 (차단)  
- 포트 선택 (와이어샤크로 패킷캡처)  
- 프로그램 선택 (파일경로)  
- IP 선택  (범위)  

Ctrl + R : 화면 

### 필터링
not arp     
ip.addr == 40.77.226.13 and not arp  
ip.addr == 27.0.236.201 and not arp and tcp  
ip.addr == 210.103.251.39 and not arp and not icmp and not tcp.port == 60794  

// 
ip.addr == 27.0.236.68


### 포트 보는법
statistics - > conversations -> tcp -> limit to display filter  
