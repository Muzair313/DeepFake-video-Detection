# DeepFake-video-Detection

## Deepfake Video Detection Based on MesoNet with Preprocessing Module
With the development of computer hardware and deep learning, face manipulation videos represented by Deepfake have been widely spread on social media. From the perspective of symmetry, many forensics methods have been raised, while most detection performance might drop under compression attacks. To solve this robustness issue, this Project proposes a Deepfake video detection method based on MesoNet with preprocessing module. First, the preprocessing module is established to preprocess the cropped face images, which increases the discrimination among multi-color channels. Next, the preprocessed images are fed into the classic MesoNet. The detection performance of proposed method is verified on datasets; and can reach 0.943 on Celeb-DF. More importantly, even in the case of heavy compression, the detection rate can still be more than 88%.




DataSet  Celeb-DF (https://paperswithcode.com/dataset/celeb-df)

