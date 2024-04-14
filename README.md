# Recipe Generator - Intel oneAPI
## Description
   The Recipe generator model I developed with **Intel oneAPI Toolkits** is designed to simplify meal planning and enhance culinary creativity. By entering available ingredients, the model instantly provides personalized recipe suggestions, helping users make the most of what they have on hand. This solution addresses the common problem of deciding what to cook with limited ingredients, reducing food waste and adding variety to daily meals. 

## Solution
The recipe generator model presents a cutting-edge solution to culinary challenges by providing personalized recipe recommendations based on user-inputted ingredients. By leveraging the capabilities of GPT-2 and Intel Extension for PyTorch, the model efficiently analyzes available ingredients and matches them with a custom-trained recipe dataset. This approach enables the generation of tailored recipes that cater to individual preferences and dietary restrictions. Users benefit from diverse, creative meal options, reducing food waste and enhancing their cooking experience. By integrating seamlessly into applications or devices, the model offers a convenient and innovative way to transform meal planning and inspire culinary exploration.
## OneAPI
OneAPI is an open, cross-architecture programming model that enables developers to write applications that can run on a variety of hardware platforms, including CPUs, GPUs, and FPGAs. The goal of oneAPI is to provide a common interface that can be used across different hardware architectures, reducing the complexity of developing software for heterogeneous systems. With oneAPI, developers can write code in standard programming languages such as C++, DPC++, and Fortran, and then use oneAPI libraries to take advantage of hardware-specific optimizations.

  ![image](https://github.com/noornish/Recipe_generator/assets/100520538/9c6b2d88-36b0-4dba-a340-257cc9ee4507)


## Model Training using  Intel DevCloud 
Leveraging Intel Extension for PyTorch, our recipe generator model benefits from the accelerated development and deployment processes facilitated by Intel Developer Cloud. By harnessing Intel's GPU capabilities, we've significantly reduced training times, ensuring efficient model optimization and experimentation. This collaborative approach has led to remarkable speedups, enhancing the overall performance of our Recipe Generation model and streamlining the culinary creativity process.

## Results

There is no difference between the accuracy when the model is trained in colab and intel developer cloud. But the training time is reduced 99% in intel devcloud when compared to the training time in colab. Notably, a single epochs takes 176 minutes to train in colab but when trained using intel devcloud libraries , it takes 0.39 minutes for single epochs.
