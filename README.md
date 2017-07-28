# Nơi tập hợp các công cụ triển khai OpenStack 

## Nhóm phát triển
- Nhóm phát triển: #VietStack Team
- Nhóm test: #hocchudong Team

### Mô hình

![noha_openstack_topology.png](./images/noha_openstack_topology.png)

### IP Planning
![noha_ip_planning.png](./images/noha_ip_planning.png)

# Danh mục các công cụ.
## Script cài đặt OpenStack Newton - không có HA
- Link hướng dẫn: 
[Hướn dẫn sử dụng script cài đặt OpenStack Newton không HA](https://github.com/vietstacker/openstack-deploy-tools/tree/master/scripts/OpenStack-Newton-No-HA)
### Thông tin về script cài đặt OpenStack Newton không có HA

- Script dùng để tìm hiểu, dựng PoC với phiên bản OpenStack Newton - triển khai trên CentOS7.
- Các project gồm có: Keystone, Glance, Cinder,Nova, Neuton, Ceilometer,Gnocchi, AODH, Swift.
- Về Neutron: 
 - Sử dụng Linux Bridge - `done`
 - Sử dụng đồng thời provider và selfservice network - `done`
- Cinder: Cung cấp tùy chọn cài đặt AIO hoặc tách node cinder. - `done`
- Swift: sử dụng 02 node swift - `done`
- Ceilometer, Gnocchi, AODH - `done`
- Tích hợp CEPH - `in progress`