Importante: Para execução é necessário instalação da biblioteca OpenCV e definição dos diretórios nas propriedades do projeto VS.

<hr>

<h2> Tela da Aplicação: </h2>

- Criei 17 filtros possíveis, eles são aplicados por cima do filtro atual, com exceção dos ultimos 4 filtros.
- Criei 5 opções de Sticker, com tamanho pré-definido. É necesário selecionar o Sticker e depois clicar na foto para aplicar.
- Criei 3 botões de menu: Salvar, Reverter, Alternar Foto/Camera.

![image](https://user-images.githubusercontent.com/58199187/174677833-a7be11f8-b58f-4b9f-9aac-2e7338fa1058.png)

Ao abrir a aplicação é necessário inserir o nome da imagem para abrir. A imagem deve ser jpg e estar na pasta textures.

![image](https://user-images.githubusercontent.com/58199187/174691537-50d2d268-58a4-4698-9472-dbeeb946adc7.png)


Para aplicar os filtros basta clicar nas miniaturas. Os filtros são sobrepostos (com exceção dos últimos 4). Para desfazer os filtros é necessário redefinir a imagem clicando no botão "reverter". 

![image](https://user-images.githubusercontent.com/58199187/174691560-132a4fb7-90bf-4616-a9c4-d124152dd94f.png)

Menos brilho / GrayScale /  Negativo  /  Canny  /  Sobel  /  Laplace

![image](https://user-images.githubusercontent.com/58199187/174693415-2041c263-b949-4554-85c1-2ed46da97d0b.png) ![image](https://user-images.githubusercontent.com/58199187/174693471-cc6b433f-c660-4ab2-9782-f6257fea672d.png) ![image](https://user-images.githubusercontent.com/58199187/174693878-592b3df0-c5b0-43a9-a0b4-2fa0a7882c01.png) ![image](https://user-images.githubusercontent.com/58199187/174693892-7c8183dc-546f-4590-ae1f-10bb8c4040e0.png)  ![image](https://user-images.githubusercontent.com/58199187/174693914-aebdbd00-587b-4c11-9f2b-ab38884a89fa.png) ![image](https://user-images.githubusercontent.com/58199187/174693946-86fa41ed-3d81-47eb-a238-8395ba2c5634.png) 

Mais Brilho  /  Blur   /  Tons Quentes / Tons Frios / Moon  /  Binarização

![image](https://user-images.githubusercontent.com/58199187/174693966-19e1a06e-6185-4f88-b5c3-fabaead61b6b.png) ![image](https://user-images.githubusercontent.com/58199187/174694180-f7058c63-b449-43f8-9017-d1babb9a31f9.png) ![image](https://user-images.githubusercontent.com/58199187/174694198-9cf9a8f4-16f9-48ec-ae77-bde158eaaaa8.png) ![image](https://user-images.githubusercontent.com/58199187/174694216-2ca2bc82-b1c8-4c45-9fad-c57d7f779d45.png) ![image](https://user-images.githubusercontent.com/58199187/174694229-206d403c-141e-43ae-97ef-5a1d3415e56c.png) ![image](https://user-images.githubusercontent.com/58199187/174694249-f891bb56-8ba4-4a23-b441-eef09cc872fe.png)

Erode / Enhance / Pencil / PencilGrayScale / Stilização

![image](https://user-images.githubusercontent.com/58199187/174694486-827653d0-b40a-4001-a12a-8264c15b5727.png) ![image](https://user-images.githubusercontent.com/58199187/174694499-e935cc23-754f-445a-a617-78b30a0404c9.png) ![image](https://user-images.githubusercontent.com/58199187/174694519-f02c6c53-b001-4712-a5d2-1e4ed5fe18b2.png) ![image](https://user-images.githubusercontent.com/58199187/174694539-b3b99603-7ad3-45a2-87cf-d42c164f8089.png) ![image](https://user-images.githubusercontent.com/58199187/174694561-577e0238-148d-408e-ba4e-958b531fad68.png)




Para aplicar os stickers é necessário escolher o Sticker e após clicar na imagem para posicioná-lo.

![image](https://user-images.githubusercontent.com/58199187/174691651-9618311e-be0d-4042-ad3e-33236c1c75d2.png)

Na parte superior estão os botões:

![image](https://user-images.githubusercontent.com/58199187/174691718-a583b187-de84-42b7-ac66-197f76dfad64.png) Alternar entre modo foto/câmera

![image](https://user-images.githubusercontent.com/58199187/174691766-ce0861ba-b999-4ecc-8252-a4b1f7d1c3d9.png) Reverter todas as alterações

![image](https://user-images.githubusercontent.com/58199187/174691806-09ca0cf3-0e2e-4399-999d-b5506f9d9dc0.png) Salvar imagem (ou frame atual da câmera)
