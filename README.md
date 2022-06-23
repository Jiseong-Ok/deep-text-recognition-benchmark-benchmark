# deep-text-recognition-benchmark-benchmark

Goal : Korean-text-Recognition

Dataset : textinthewild dataset in AI Hub
- Book
- Goods
- Signboard
- Traffic_Sign

Model : TPS-ResNet-BiLSTM-CTC(STAR-Net)

Result
- best val acc : 91% in 70000iteration(batch_size=96)

Ongoing
- Data Augmentation : straug(https://github.com/roatienza/straug.git)
- Example(Rotate, DefocusBlur)

![Augmentation](https://user-images.githubusercontent.com/106142675/175199268-adb54061-d27e-4eac-b450-fb699d8df98a.png)

- Super Resolution : SwinIR(https://github.com/jingyunliang/swinir)

![Super Resolution](https://user-images.githubusercontent.com/106142675/175199377-c2437ec0-0f94-4e97-b548-f7a0b4568bd9.png)


Reference
- https://github.com/clovaai/deep-text-recognition-benchmark.git
- https://github.com/roatienza/straug.git
- https://github.com/jingyunliang/swinir
- https://cvml.tistory.com/21
