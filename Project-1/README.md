# Classifier Reviews

Se utiliza regresión logistica con penalización **Ridge** y **Lasso** para realizar una clasificación binaria según la autenticidad de comentarios a hoteles, utilizando un corpus de 1600 opiniones a hoteles de Chicago. Este corpus consiste en críticas falsas y autenticas de 20 hoteles de Chicago. Los datos fueron originalmente descritos en dos documentos de acuerdo con el sentimiento positivo o negativo de los mismos:
 
 Este corpus contiene:
 
 - 800 comentarios auténticos, de los cuáles 400 están clasificados como positivos y 400 como negativos
 - 800 comentarios falsos, igualmente dividio en 400 comentarios positvas y 400 negativos.
 
La vectorización de los textos se realiza utilizando la técnica _Bag of Words_ (BoW), de manera que se obtiene una matriz de 1600 documentos por 3,528 palabras.
 
 El conjunto de datos original puede ser descargado [aquí](https://myleott.com/op-spam.html). Este mismo ha sido también publicado por [Kaggle](https://www.kaggle.com/datasets/rtatman/deceptive-opinion-spam-corpus) en un archivo csv, el cual ha sido copiado en el presente repositorio.
 
 
 [1] M. Ott, Y. Choi, C. Cardie, and J.T. Hancock. 2011. Finding Deceptive Opinion Spam by Any Stretch of the Imagination. In Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies.
 
 [2] M. Ott, C. Cardie, and J.T. Hancock. 2013. Negative Deceptive Opinion Spam. In Proceedings of the 2013 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies.
