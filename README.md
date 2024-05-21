<div align="center">
<a href="z"><img src="https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Bitcoin-000000?style=for-the-badge&logo=bitcoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=Ethereum&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Litecoin-A6A9AA?style=for-the-badge&logo=Litecoin&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white"/></a>
<a href="z"><img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a>
</div>


<p align="center">
  <img src="https://github.com/matyo91/matyo91/raw/main/assets/github.gif" alt="Hi, I'm Mathieu 👋 I'm a 🚀 French developer 🚀 I ❤️ Happy Hardcore ❤️">
</p>


```mermaid
erDiagram
CLIENT {
  string id PK
  string name
  string email
}

POST {
  string id PK
  string clientId FK
  string content
  datetime created_at
}

AUTH {
  string id PK
  string clientId FK
  bool authenticated
  datetime auth_time
}

SYSTEM {
  string id PK
  string requestId FK
  string processResult
  datetime processed_at
}

CLIENT ||--o{ POST: "sends"
POST ||--o| AUTH: "requires"
AUTH ||--|| SYSTEM: "accesses"
SYSTEM ||--o{ CLIENT: "returns response to"
```

<p align="center">
    <img src="https://minkxx-spotify-readme.vercel.app/api?theme=dark&rainbow=true&scan=true&spin=True" alt="Preview">
</p>

<p align="center">
  <img src="https://github.com/tarikmanoar/tarikmanoar/raw/output/github-snake-dark.svg" alt="snake"></center>
</p>
