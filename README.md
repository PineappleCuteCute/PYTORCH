# Các ví dụ PyTorch

![Chạy ví dụ](https://github.com/pytorch/examples/workflows/Run%20Examples/badge.svg)

https://pytorch.org/examples/

`pytorch/examples` là một kho lưu trữ giới thiệu các ví dụ sử dụng [PyTorch](https://github.com/pytorch/pytorch). Mục tiêu là cung cấp các ví dụ **chất lượng cao**, ngắn gọn, ít hoặc không có phụ thuộc, có sự khác biệt đáng kể và có thể áp dụng vào công việc hiện tại của bạn.

- Hướng dẫn: [https://github.com/pytorch/tutorials](https://github.com/pytorch/tutorials)
- Đóng góp thay đổi cho pytorch.org: [https://github.com/pytorch/pytorch.github.io](https://github.com/pytorch/pytorch.github.io)
- Kho mô hình tổng quát: [https://pytorch.org/hub/](https://pytorch.org/hub/) hoặc [https://huggingface.co/models](https://huggingface.co/models)
- Công thức triển khai PyTorch trong sản xuất: [https://github.com/facebookresearch/recipes](https://github.com/facebookresearch/recipes)
- Hỏi đáp và hỗ trợ: [https://discuss.pytorch.org/](https://discuss.pytorch.org/)

## Các mô hình có sẵn

- [Phân loại ảnh (MNIST) sử dụng Convnets](./mnist/README.md)
- [Mô hình hóa ngôn ngữ ở cấp từ sử dụng RNN và Transformer](./word_language_model/README.md)
- [Huấn luyện bộ phân loại Imagenet với các mạng phổ biến](./imagenet/README.md)
- [Mạng đối kháng tạo sinh (DCGAN)](./dcgan/README.md)
- [Auto-Encoders biến phân](./vae/README.md)
- [Siêu phân giải sử dụng mạng tích chập hiệu quả dưới mức điểm ảnh](./super_resolution/README.md)
- [Huấn luyện đồng thời ConvNets trên MNIST với Hogwild](mnist_hogwild)
- [Huấn luyện CartPole để cân bằng trong OpenAI Gym với actor-critic](./reinforcement_learning/README.md)
- [Suy luận ngôn ngữ tự nhiên (SNLI) với GloVe, LSTMs và torchtext](snli)
- [Dự đoán chuỗi thời gian - sử dụng LSTM để học sóng Sine](./time_sequence_prediction/README.md)
- [Triển khai thuật toán Neural Style Transfer trên ảnh](./fast_neural_style/README.md)
- [Học tăng cường với các thuật toán Actor-Critic và REINFORCE trên OpenAI Gym](./reinforcement_learning/README.md)
- [Chuyển đổi mô-đun PyTorch bằng fx](./fx/README.md)
- Các ví dụ PyTorch phân tán với [Distributed Data Parallel](./distributed/ddp/README.md) và [RPC](./distributed/rpc)
- [Một số ví dụ minh họa giao diện C++](cpp)
- [Phân loại hình ảnh sử dụng Forward-Forward](./mnist_forward_forward/README.md)
- [Dịch ngôn ngữ bằng Transformers](./language_translation/README.md)

Danh sách các ví dụ chất lượng tốt được lưu trữ trong kho riêng:

- [Dịch máy thần kinh sử dụng sequence-to-sequence RNN với attention (OpenNMT)](https://github.com/OpenNMT/OpenNMT-py)

## Đóng góp

Nếu bạn muốn đóng góp ví dụ của mình hoặc sửa lỗi, hãy tham khảo [CONTRIBUTING.md](CONTRIBUTING.md).