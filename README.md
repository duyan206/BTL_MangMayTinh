# Thiết kế hạ tầng mạng nội bộ - Công ty AL
**Môn học:** Mạng máy tính | **Trường:** Đại học Đại Nam

## 1. Giới thiệu dự án
Dự án thiết kế và mô phỏng hệ thống mạng LAN cho doanh nghiệp nhỏ bằng Cisco Packet Tracer. Kiến trúc bao gồm phân tách VLAN, định tuyến Inter-VLAN và tự động hóa cấp phát IP (DHCP).

## 2. Sơ đồ kiến trúc (Topology)
![Sơ đồ mạng](link_ảnh_topology_của_mày_up_lên_github)

## 3. Quy hoạch IP (VLSM)
* **VLAN 10 (Giám đốc):** 192.168.10.0/26
* **VLAN 20 (Nhân viên):** 192.168.10.64/26
* **VLAN 100 (Server):** 192.168.10.128/26

## 4. Công nghệ sử dụng
* Inter-VLAN Routing (Router-on-a-stick)
* DHCP & DHCP Relay (IP Helper-address)
* VLAN & Trunking (802.1Q)
