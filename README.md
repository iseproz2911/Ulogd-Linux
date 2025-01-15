# Ulogd-Linux
Ulogd is a daemon that reports issues related to netfilter/iptables. This includes security breach reporting and per-packet auditing. Ulogd also allows flexible security reporting and auditing (customized by the user) on each traffic flow.

Tìm hiểu các plugins 

Input plugins: ULOG, NFLOG, NFCT 

Output plugins: LOGEMU, OPRINT, SYSLOG, MYSQL, PGSQL, SQLITE3, PCAP, IPFIX, NACCT, JSON 

Tìm hiểu những plugins hỗ trợ trên Ulogd trên WebOS hiện tại. 

Xây dựng Ulogd tuỳ biến dựa vào các plugins 

Xây dựng Ulogd tuỳ biến để báo cáo các vi phạm/ kiểm toán về gói tin/ luồng lưu lượng (tất nhiên cần xây dựng trước chính sách bảo mật --> iptables --> kiểm tra vi phạm/kiểm toán dựa vào Ulogd tuỳ biến). 


Link Report: https://hackmd.io/@iamproz2911/SknRkj0NJe
