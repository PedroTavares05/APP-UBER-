# Uber Clone

Este é um projeto de aplicativo de transporte desenvolvido com Flutter. Ele simula funcionalidades básicas de um aplicativo de transporte como Uber, incluindo cadastro de usuários, autenticação, solicitação de corridas e acompanhamento em tempo real.

## Sobre o Projeto

Este projeto foi desenvolvido como parte do curso da Udemy, com o objetivo de aprender e praticar o desenvolvimento de aplicativos móveis utilizando Flutter. Ele utiliza diversas tecnologias modernas, como Firebase para backend e Google Maps para exibição de mapas e rotas.

## Estrutura do Projeto

Abaixo está a estrutura completa do projeto, incluindo os principais arquivos e diretórios:
uber/ ├── android/ # Arquivos de configuração e código específico para Android ├── ios/ # Arquivos de configuração e código específico para iOS ├── lib/ # Código principal do aplicativo em Flutter │ ├── main.dart # Arquivo principal do aplicativo │ ├── screens/ # Telas do aplicativo │ ├── models/ # Modelos de dados │ ├── controllers/ # Lógica de controle e gerenciamento de estado │ └── widgets/ # Componentes reutilizáveis ├── test/ # Testes do aplicativo ├── pubspec.yaml # Arquivo de configuração do Flutter e dependências ├── .gitignore # Arquivo para ignorar arquivos/diretórios no Git ├── README.md # Documentação do projeto └── LICENSE # Licença do projeto

Instale as dependências:

Configure o Firebase:

Baixe os arquivos google-services.json (Android) e GoogleService-Info.plist (iOS) do Firebase e coloque-os nos diretórios apropriados.
Adicione a chave da API do Google Maps:

No Android, configure a chave no arquivo android/app/src/main/AndroidManifest.xml.
No iOS, configure a chave no arquivo ios/Runner/AppDelegate.swift.
Execute o aplicativo:

Para Android:
Para iOS:
Estrutura de Pastas do Código Flutter
lib/main.dart: Ponto de entrada do aplicativo.
lib/screens/: Contém as telas do aplicativo, como login, cadastro, mapa, etc.
lib/models/: Modelos de dados, como usuário e corrida.
lib/controllers/: Gerenciamento de estado e lógica de negócios.
lib/widgets/: Componentes reutilizáveis, como botões e caixas de texto.
Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Nota: Este projeto foi desenvolvido para fins educacionais como parte de um curso da Udemy. Não é destinado para uso em produção.

## Funcionalidades do Projeto

- **Cadastro e autenticação de usuários**: Integração com Firebase Authentication.
- **Diferenciação entre motoristas e passageiros**: Interface e funcionalidades específicas para cada tipo de usuário.
- **Solicitação de corridas**: Passageiros podem solicitar corridas e motoristas podem aceitar.
- **Acompanhamento em tempo real**: Rastreamento da localização do motorista e do passageiro utilizando Google Maps.
- **Integração com Firebase**: Utilizado para autenticação, banco de dados em tempo real e armazenamento.
- **Uso do Google Maps**: Exibição de mapas, rotas e cálculo de distâncias.

## Tecnologias Utilizadas

- **Flutter**: Framework para desenvolvimento multiplataforma.
- **Firebase**:
  - Firebase Authentication
  - Cloud Firestore
  - Firebase Realtime Database
- **Google Maps API**: Para exibição de mapas e rotas.
- **Geolocator**: Para obter a localização do usuário.
- **Intl**: Para formatação de datas e valores.

## Dependências

As principais dependências utilizadas no projeto estão listadas no arquivo `pubspec.yaml`. Algumas delas incluem:

- `firebase_core`: Integração com o Firebase.
- `firebase_auth`: Autenticação de usuários.
- `cloud_firestore`: Banco de dados em tempo real.
- `google_maps_flutter`: Exibição de mapas.
- `geolocator`: Obtenção de localização.
- `intl`: Formatação de dados.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes itens instalados:

- Flutter SDK (versão compatível com o projeto)
- Android Studio ou Xcode (para emulação e execução em dispositivos)
- Conta no Firebase configurada com os serviços necessários
- Chave de API do Google Maps configurada

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd uber-clone

2. Instale as dependências:
flutter pub get

3.Configure o Firebase:

- Baixe os arquivos google-services.json (Android) e GoogleService-Info.plist (iOS) do Firebase e coloque-os nos diretórios apropriados.

4. Adicione a chave da API do Google Maps:

- No Android, configure a chave no arquivo android/app/src/main/AndroidManifest.xml.
- No iOS, configure a chave no arquivo ios/Runner/AppDelegate.swift.
Execute o aplicativo:

- Para Android:
flutter run

Para iOS:

flutter run

Estrutura de Pastas do Código Flutter
lib/main.dart: Ponto de entrada do aplicativo.
lib/screens/: Contém as telas do aplicativo, como login, cadastro, mapa, etc.
lib/models/: Modelos de dados, como usuário e corrida.
lib/controllers/: Gerenciamento de estado e lógica de negócios.
lib/widgets/: Componentes reutilizáveis, como botões e caixas de texto.
Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

Nota: Este projeto foi desenvolvido para fins educacionais como parte de um curso da Udemy. Não é destinado para uso em produção. 
