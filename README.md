# 备用系统装机教程
1. 插上 u 盘，u 盘启动，看到 install centos7 回车
2. 选择绿框内，手动分区
<img width="480" alt="image" src="https://github.com/user-attachments/assets/6c900617-4240-4fdf-8383-98a97fdbbddf">
3. 选择系统盘，并点击手动分区，然后点击左上角 Done（若没反应，多点几次）
<img width="496" alt="image" src="https://github.com/user-attachments/assets/7f0e028c-ae4d-41d2-bfe9-ba2f7e2e57af">
4. 点击 LVM，选择标准分区
<img width="489" alt="image" src="https://github.com/user-attachments/assets/c648a061-8028-4450-a00d-1bcbe3a71dc3">
5.选择+开始分区/boot 2G，/50G，/home 60G，可以手动敲，也可以选倒三角（/home需要手敲）创建完成后重复点击+号直到三个分区创建完成（/boot，/，/home）
<img width="488" alt="image" src="https://github.com/user-attachments/assets/729f9aa2-e9e6-41f8-a10b-7cf0aad4248b">
6.分区完成后效果如下,需要检查分区格式，必须位 ext4，若不是请修正，随后第二步update settings 更新，然后 Done（若无反应多按几次）
<img width="537" alt="image" src="https://github.com/user-attachments/assets/a35a456e-c893-4457-a7c4-0cacc662c3f1">
7. 点击 Done 后，有个确认点击 Accept Changes
<img width="533" alt="image" src="https://github.com/user-attachments/assets/9f099951-7fae-4883-ba3f-cb670bcba78a">
8.确认后，开始安装
<img width="504" alt="image" src="https://github.com/user-attachments/assets/b0fa8dc9-70e5-4f56-8cd6-77c72a664d56">
9.系统开始安装，随后设置下 root 密码建议 123456，随后点 done，没反应多点几次
<img width="510" alt="image" src="https://github.com/user-attachments/assets/fb3d8be1-125f-42e0-b384-14ccb66e9885">
10.等待系统自动安装即可，安装完成后点击 Reboot 重启，点击 reboot 后拔盘，完成安装
<img width="504" alt="image" src="https://github.com/user-attachments/assets/35118e3c-4b28-4f68-b271-93e51ca4e710">
  



