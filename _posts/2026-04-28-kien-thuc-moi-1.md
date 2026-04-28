---
layout: page
title: "Thử bắt đâu Python-React-Web Stack"
date: 2026-04-28
categories: [kien-thuc-moi]
---

Khi tìm hiểu về thị trường việc làm hiện nay, mình thấy những cái tên như Python, React, API hay JavaScript xuất hiện liên tục. <br>
Trong khi mình chỉ có kinh nghiệm về nhúng, các thanh ghi, bộ nhớ, bit, byte..thi thế giới Web đối với mình mờ mịt và chằng chịt ko thể hiểu nổi. <br>
Và mình quyết định thử tìm hiểu cách chúng vận hành như thế nào,kết nối với nhau ra sao, dữ liệu đi như thế nào, nên mình đã thử làm một ứng dụng nhỏ với sự hỗ trợ của AI. <br>
Mục đích là tạo ra một giao diện đơn giản để kiểm tra trạng thái On/Off của các LXD Container trên máy mình. <br>


<img src="https://the-peaceful-drawer.github.io/assets/img/containerstatus2.png" 
     alt="Python" 
     style="width: 100%; max-width: 500px; display: block; margin: 2rem auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">

     
<img src="https://the-peaceful-drawer.github.io/assets/img/containerstatus2.png" 
     alt="LXD Container" 
     style="width: 100%; max-width: 500px; display: block; margin: 2rem auto; border-radius: 12px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">

Qua dự án này, mình đã nắm được những khái niệm cơ bản:

    Backend: Mình dùng Python để viết các API. Phần này đóng vai trò xử lý bên dưới, trực tiếp truy cập vào hệ thống để lấy dữ liệu từ Container.<br>

    Frontend: Mình sử dụng React và JavaScript để xây dựng giao diện người dùng. Đây là nơi hiển thị trạng thái của các container để mình có thể quan sát trực quan.<br>

    Kết nối: Mình hiểu được luồng dữ liệu đi từ Frontend đến Backend thông qua các yêu cầu (request). Dữ liệu phản hồi được trả về dưới dạng JSON – một định dạng chung giúp hai bên "nói chuyện" được với nhau.

Dù chỉ mới bắt đầu nhưng việc tự tay kết nối các thành phần từ Python ở Backend đến React ở Frontend đã giúp mình không còn bỡ ngỡ với các thuật ngữ Web nữa.  <br>
Thay vì chỉ đọc lý thuyết, việc thấy ứng dụng thực sự hoạt động giúp mình có cái nhìn rõ ràng hơn về cấu trúc của một hệ thống Web hiện đại.
Vì có quá nhiều thứ ở hiện tai mà mình muốn học, nên tạm thời mình sẽ gác lại đó, hoặc có thể kết hợp kiến thức này trong một ứng dụng khác. 
