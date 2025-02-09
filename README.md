# Flume: Các bước chạy một chương trình flume.

Sau khi tải flume về máy phải vào thư mục conf nằm ở trong thư mục sau khi đã giải nén và chỉnh sửa file flume-env.sh.

Tạo file conf 

Chú ý nếu muốn log xuất hiện trên console và cả file flume.log(Sau khi chạy 1 agent sẽ có) thì vào phần log4j2.xml trong thư mục conf để chỉnh sửa.

Câu lện chạy chương trình: flume-ng agent --conf $FLUME_HOME/conf --conf-file conf.conf --name a1

Sau khi chạy mở một another terminal và nhập: telnet localhost 44444

Kết quả: Những gì nhập ở telnet sẽ lần lượt được hiển thị ở console ở terminal chạy flume duới dạng event.
