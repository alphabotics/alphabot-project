# ALPHABOT

ALPHABOT is an open source humanoid robot which is developed based on Python for inside AI Brain.

ALPHABOT là một con robot với hình dáng cơ thể của nó được xây dựng để giống với con người cơ thể. Thiết kế có thể dành cho các mục đích chức năng, chẳng hạn như tương tác với các công cụ và môi trường của con người, cho các mục đích thử nghiệm.

PROJECT DESCRIPTION

MÔ TẢ KIẾN TRÚC PROJECT

1. Dự án sẽ được xây dựng trên kiến trúc microservice.
2. Mỗi servie là một tính năng cho Robot cung cấp API cho các module bên ngoài giao tiếp với nó.

    2.1. Tính năng nhìn (quan camera) sẽ được thiết kế như một service riêng dựa trên Machine Learning và Jetson Nano board vì board này cung cấp các lõi GPU tối ưu cho việc chạy Machine Learning.

    2.1. Chức năng nghe, nói sẽ tích hợp Speed to Text phân tích giọng nói dựa trên một số nguồn mở có sãn như VAIS của Vietnam.

    2.2. Chức năng điều khiển các thành phần cơ thể Robot như tay, chân robot sẽ được phát triển thành 1 s
  
TODO


## ALPHABOT Cores

A collection of much microservice based on Kubernetes such as image processing, video processing, hardware controllers,..etc which is used to make communication between brain's features, brain's network, body's hardware.

*Một bộ sưu tập nhiều dịch vụ siêu nhỏ như xử lý hình ảnh, xử lý video, bộ điều khiển phần cứng, v.v ... được sử dụng để thực hiện giao tiếp giữa các tính năng của não, mạng của não, phần cứng của cơ thể.*


## ALPHABOT Features

A collection of features like humans is developed like API Gateway to communicate to real life based on Go programming language.

*Một tập hợp các tính năng như con người bao gồm nghe, nói, đọc, tương tác được phát triển như API Gateway để giao tiếp với cuộc sống thực dựa trên ngôn ngữ lập trình Python.*

## ALPHABOT Brain

A brain network is a collection of neurons.
The brain of this robot is developed based on Artificial Intelligence using Python programming language.a

*Bộ não của robot này được phát triển dựa trên một mạng tập hợp các tế bào thần kinh tạo nên hệ trí tuệ nhân tạo cho robot*
