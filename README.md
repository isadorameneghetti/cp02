# Sistema de Consultas Médicas - Mobile

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

## INTEGRANTES DO GRUPO

| Nome | RM |
|------|-----|
| **Isadora Meneghetti** | RM556326 |
| **Henrique Azevedo** | RM556707 |

---

## SOBRE O PROJETO

Aplicativo mobile de **Sistema de Consultas Médicas** desenvolvido em React Native com TypeScript. Permite visualizar e gerenciar consultas médicas, com funcionalidades de gerenciamento de status, autenticação de usuários e persistência de dados.

---

## FUNCIONALIDADES

- Visualização detalhada de consultas médicas
- Gerenciamento de status (agendada, confirmada, cancelada, realizada)
- Confirmação e cancelamento de consultas
- Formatação de valores monetários (R$)
- Formatação de datas no padrão brasileiro
- Tipagem forte com TypeScript
- Interface responsiva com cards
- Feedback visual baseado no status
- Persistência de dados com AsyncStorage
- Autenticação de usuários (admin/paciente)
- Navegação entre telas com React Navigation
- Context API para gerenciamento de estado global

---

## TECNOLOGIAS UTILIZADAS

- React Native
- Expo
- TypeScript
- React Navigation
- AsyncStorage
- Context API
- React Hooks (useState, useEffect)

---

## COMO EXECUTAR

### Pré-requisitos
- Node.js
- Expo CLI
- Expo Go (celular)

### Passos

```bash
# Instale as dependências
npm install

# Execute o projeto
npx expo start
```

---

## CREDENCIAIS DE TESTE

| Perfil | Email | Senha |
|--------|-------|-------|
| Admin | admin@sistema.com | admin123 |
| Paciente | joao@email.com | 123456 |
| Paciente | maria@email.com | 123456 |

---

## ESTRUTURA DE PASTAS

```
consultas-mobile/src/
├── components/      # Componentes reutilizáveis
├── contexts/        # Context API (AuthContext)
├── interfaces/      # Interfaces TypeScript
├── navigation/      # Configuração de rotas
├── screens/         # Telas do aplicativo
├── services/        # Service layer (AsyncStorage)
├── styles/          # Estilos separados
├── types/           # Type aliases
└── utils/           # Funções utilitárias
```

---

## DISCIPLINA

**Mobile Development e IoT**

Professor: Hete Caetano dos Santos

FACULDADE FIAP - 2026

---

## LICENÇA

Desenvolvido para fins educacionais. Todos os direitos reservados.
