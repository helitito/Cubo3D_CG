# Cubo 3D com Three.js

## 📖 Descrição
Este projeto apresenta uma cena 3D utilizando a biblioteca [Three.js](https://threejs.org/).  
Na cena, um cubo verde é exibido sobre um chão branco, projetando sombra graças ao uso de iluminação e ao sistema de sombras do renderizador.  
O usuário pode interagir com a câmera em perspectiva, rotacionando, aplicando zoom e movimentando a visualização com o mouse.

---

## 🚀 Instruções de Execução
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/cubo-3d-threejs.git

2. Acesse a pasta do projeto:
   cd cubo-3d-threejs

3. Abra o arquivo index.html em um navegador moderno (Chrome, Firefox, Edge).

  💡 Não é necessário instalar dependências, pois o projeto utiliza CDN para carregar o Three.js e OrbitControls.


🎮 Interação- Rotação da câmera: clique e arraste com o botão esquerdo do mouse.
- Zoom: use a rolagem do mouse.
- Movimentação lateral da câmera: clique e arraste com o botão direito do mouse.
  O cubo permanece parado, mas a câmera pode ser manipulada livremente para observar o objeto sob diferentes ângulos.🔦 Uso da Câmera e da Perspectiva- A câmera utilizada é do tipo PerspectiveCamera, que simula a visão humana, permitindo perceber profundidade na cena.
- O sistema de OrbitControls possibilita a interação com a câmera de forma intuitiva.
- O renderizador ajusta automaticamente a proporção da câmera e o tamanho da tela ao redimensionar a janela, garantindo que a visualização permaneça correta.
 
✨ Recursos Implementados
- Cubo 3D verde visível na cena.
- Chão branco que recebe sombra.
- Iluminação direcional que projeta sombra do cubo.
- Câmera em perspectiva configurada corretamente.
- Interação com o mouse (rotação, zoom e movimentação).
- Ajuste automático ao redimensionar a janela.


