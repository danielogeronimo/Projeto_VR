# 🥽 Projeto VR 01

Este é um projeto de realidade virtual desenvolvido na Unity, com suporte nativo para dispositivos Oculus e otimizações de desempenho.

---

## 🧠 Sobre o Projeto

O projeto foi criado para explorar e implementar funcionalidades de realidade virtual usando o **Universal Render Pipeline (URP)**. Ele serve como base para o desenvolvimento de experiências interativas para headsets VR, com foco no ecossistema Oculus.

---

## 🛠️ Tecnologias Utilizadas

- Unity (com suporte VR ativado)
- Universal Render Pipeline (URP)
- Oculus Integration
- Adaptive Performance
- Composition Layers (OVR)

---

## 📁 Estrutura do Projeto

```plaintext
Projeto_VR_01/
├── Assets/
│   ├── Adaptive Performance/     # Configurações de performance adaptativa
│   ├── CompositionLayers/        # Camadas de composição do Oculus
│   ├── Material/                 # Materiais (marrom, vidro)
│   ├── Oculus/                   # SDK e configurações Oculus
│   └── Plugins/Android/          # Plugins para Android
├── Packages/                     # Manifesto e dependências do Unity
├── ProjectSettings/              # Configurações gerais do projeto
├── UserSettings/                 # Configurações locais do usuário
├── Asset Bundles/                # Pacotes de assets (se aplicável)
├── .vsconfig                     # Configuração do Visual Studio
└── README.md                     # Este arquivo
⚙️ Pré-requisitos
Unity 2020.3 LTS ou superior com suporte ao Universal Render Pipeline (URP)

Oculus Integration instalado via Unity Asset Store ou Package Manager

Oculus PC SDK ou Oculus Mobile SDK (dependendo da plataforma alvo)

🚀 Configuração do Ambiente
Clone o repositório:

bash
git clone https://github.com/danielogeronimo/Projeto_VR.git
Abra o projeto na Unity:
Selecione a pasta Projeto_VR_01.

Verifique o suporte VR:

Edit > Project Settings > Player > Other Settings > Virtual Reality Supported deve estar ativado.

A SDK do Oculus deve estar listada.

Configure a cena inicial:
A cena principal pode ser definida em File > Build Settings. (Se não houver uma cena configurada, crie uma nova com um OVRCameraRig)

Build para o dispositivo VR:

Para Oculus Quest: mude a plataforma para Android e configure as permissões necessárias.

Para Oculus Rift: use a plataforma Windows, Mac ou Linux.

🎮 Funcionalidades Implementadas
✅ Suporte nativo ao Oculus VR

✅ Renderização Universal (URP)

✅ Performance adaptativa para diferentes dispositivos

✅ Materiais visualmente otimizados (ex.: vidro_cubo.mat e marron.mat)

✅ Camadas de composição (Composition Layers) para interface e sobreposições

🧪 O projeto ainda está em desenvolvimento e novos recursos serão adicionados conforme necessário.

🤝 Como Contribuir
Contribuições são bem-vindas! Para contribuir:

Faça um fork do projeto.

Crie uma branch para sua feature:
git checkout -b minha-feature

Commit suas mudanças:
git commit -m 'Adiciona nova feature'

Push para a branch:
git push origin minha-feature

Abra um Pull Request no GitHub.

📄 Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais informações (caso exista).

📬 Contato
Autor: danielogeronimo

Repositório: https://github.com/danielogeronimo/Projeto_VR
