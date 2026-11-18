<!-- 1. Cái gì viết trong bài phải chắc chắn để defend được nếu reviewer hỏi

- phần 2.1.1 
1. posterior probability gần 0.5 ảnh hưởng đến tổng thể uncertainty chứ không nói là epistemic uncertainty
2. không ghi rõ ra là gần 0.5 vì ngưỡng có thể bị ảnh hưởng
3. công thức loss funciton (công thức số 2) chỉ sử dụng với decomposable loss còn trong non-decomposable loss thì không có
4. check file sminton (2021) công thức số 28 để xem công thức loss function trong bài báo đó
5. c không bắt buộc phải nhỏ hơn 0.5
6. (công thức số 3) nó chỉ sảy ra khi loss function non decomposable với giả định label independence hoặc loss function decomposable 

- phần 2.2
1. công thức số 6: trong các trường hợp independence chặt hơn thì có thể không có công thức số 6

- phần 2.3.2
1. nói rõ nguồn khi sử dụng A* hay beam search

- phần 2.3.3
1. không nên nhắc tới vì đã có người làm rồi

- phần 2.4
1. mỗi hạn chế phải có 1 nguồn chứng minh cho nó và viết lại chuẩn theo tài liệu
2. completely destroying the interpretability of label dependency graphs. khi có reviewer đọc thì có thể bị hỏi và reject vì không chặt chẽ
3. -không dùng fully connected triangular
dependency topology mà dùng fully connected dag
  -không dùng downstream classifiers vì không hợp ngữ cảnh mà dùng preceding
  -capturing unconditional co-occurrences and spurious correlations that vanish once features 𝑥 are controlled for. phải xét 2 hướng unconditional independence và conditional dependence
  -bỏ câu cuối phần causal, không nên nhầm lẫn giữa probabilistic and causality
4. khi sử dụng hamming loss thì mới có thể sử dụng score là 0.5 (khi sử dụng các loss khác thì có thể thay đổi threshold) -->