# Breast-Canser-Detection-with-Tensorflow

<div align="center">
      <H1> Beauty-product-trends</H1>
<H2>
</H2>  
     </div>

<body>
<p align="center">
  <a href="mailto:arifmiahcse952@gmail.com"><img src="https://img.shields.io/badge/Email-arifmiah%40gmail.com-blue?style=flat-square&logo=gmail"></a>
  <a href="https://github.com/Arif-miad"><img src="https://img.shields.io/badge/GitHub-%40ArifMiah-lightgrey?style=flat-square&logo=github"></a>
  <a href="https://www.linkedin.com/in/arif-miah-8751bb217/"><img src="https://img.shields.io/badge/LinkedIn-Arif%20Miah-blue?style=flat-square&logo=linkedin"></a>

 
  
  <br>
  <img src="https://img.shields.io/badge/Phone-%2B8801998246254-green?style=flat-square&logo=whatsapp">
  
</p>

```python
num_images = 6


random_indices = np.random.choice(len(x_train), num_images, replace=False)


fig, axes = plt.subplots(2, 3, figsize=(10, 7))


for i, idx in enumerate(random_indices):
    ax = axes[i // 3, i % 3]  
    ax.imshow(x_train[idx], cmap='gray')  
    ax.set_title(f"Label: {y_train[idx]}")  
    ax.axis('off')


plt.tight_layout()
plt.show()
```
