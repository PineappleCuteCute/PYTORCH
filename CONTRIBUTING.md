# Đóng góp vào dự án examples

Chúng tôi muốn việc đóng góp vào dự án này trở nên dễ dàng và minh bạch nhất có thể.

## Pull Requests

Chúng tôi hoan nghênh các pull request của bạn.

Nếu bạn là người mới, hãy tham khảo các vấn đề được gắn nhãn [good first issue](https://github.com/pytorch/examples/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

### Đối với ví dụ mới

1. **Tạo một issue trên GitHub** để đề xuất ví dụ mới và đảm bảo rằng nó khác biệt đáng kể với các ví dụ hiện có.
2. **Fork repo** và tạo nhánh từ `main`.
3. Nếu bạn thêm mã cần được kiểm tra, hãy thêm các bài kiểm tra vào file `run_python_examples.sh`.
4. Tạo một file `README.md`.
5. Thêm một card mô tả ngắn gọn về ví dụ của bạn và liên kết đến repo trong file `docs/source/index.rst`, sau đó build tài liệu bằng cách:

   ```bash
   cd docs
   virtualenv venv
   source venv/bin/activate
   pip install -r requirements.txt
   make html
   ```

   Khi làm việc xong với `virtualenv`, chạy `deactivate`.

6. Kiểm tra để đảm bảo không có lỗi trong quá trình build tài liệu. Bạn có thể xem trước bản build cục bộ bằng cách cài đặt [sphinx-serve](https://pypi.org/project/sphinx-serve/) và chạy lệnh `sphinx-serve -b build`.
7. Đảm bảo các bài kiểm tra của bạn vượt qua khi chạy cục bộ.
8. Nếu bạn chưa hoàn tất, hãy hoàn thành Thỏa thuận Cấp phép Đóng góp ("CLA").
9. Xử lý nhanh các phản hồi trong quá trình review code.

### Đối với sửa lỗi

1. **Fork repo** và tạo nhánh từ `main`.
2. Đảm bảo bạn có máy tính hỗ trợ GPU, cục bộ hoặc trên đám mây. `g4dn.4xlarge` trên AWS là một lựa chọn tốt.
3. Thực hiện thay đổi trong mã của bạn.
4. Cài đặt các phụ thuộc với lệnh `./run_python_examples.sh "install_deps"`.
5. Đảm bảo rằng `./run_python_examples.sh` chạy thành công từ đầu đến cuối.
6. Nếu bạn chưa hoàn tất, hãy hoàn thành Thỏa thuận Cấp phép Đóng góp ("CLA").
7. Xử lý nhanh các phản hồi trong quá trình review code.

## Thỏa thuận Cấp phép Đóng góp ("CLA")

Để chấp nhận pull request của bạn, chúng tôi cần bạn gửi CLA. Bạn chỉ cần thực hiện việc này một lần để đóng góp cho bất kỳ dự án mã nguồn mở nào của Facebook.

Hoàn tất CLA tại đây: <https://code.facebook.com/cla>

## Vấn đề

Chúng tôi sử dụng GitHub Issues để theo dõi các lỗi công khai. Vui lòng đảm bảo mô tả của bạn rõ ràng và có đủ hướng dẫn để tái tạo vấn đề.

## Giấy phép

Bằng cách đóng góp vào `examples`, bạn đồng ý rằng các đóng góp của mình sẽ được cấp phép theo file LICENSE trong thư mục gốc của dự án này.