# EcoTienda: Plataforma de Incentivos Sostenibles Basada en Blockchain

## Descripción General

**EcoTienda** es una plataforma diseñada para fomentar la sostenibilidad y la economía circular a través de la venta de ropa de segunda mano. El proyecto utiliza tecnologías blockchain para garantizar transparencia, seguridad y recompensas en forma de tokens a los usuarios que participen activamente en la plataforma. Estos tokens pueden ser utilizados para obtener más productos en la tienda, promoviendo la fidelización de clientes y prácticas responsables con el medio ambiente.

Este proyecto está compuesto por tres componentes principales:

1. **Smart Contracts**: Implementan la lógica del sistema de recompensas y la gestión de tokens.
2. **Frontend**: Proporciona la interfaz de usuario para interactuar con la plataforma.
3. **Backend**: Maneja la lógica del negocio, la autenticación y la comunicación con la blockchain.

## Tecnologías Utilizadas

### Blockchain
- **Blockchain utilizada**: Ethereum (testnet/local)
- **Framework de desarrollo**: Hardhat
- **Tokens**: Implementación de contratos inteligentes para el sistema de recompensas en tokens.
- **Herramientas de desarrollo**: Ganache para simulación local de blockchain.

### Frontend
- **Framework principal**: React
- **Librerías adicionales**: 
  - Vite para configuración y empaquetado del proyecto.
  - TypeScript para un desarrollo tipado.
  - Context API para la gestión de estado.
- **Diseño**: Implementación de componentes reutilizables y layouts para optimizar la experiencia de usuario.
- **Interacción con blockchain**: Uso de MetaMask para la conexión con wallets y contratos inteligentes.

### Backend
- **Framework**: NestJS
- **Base de datos**: PostgreSQL
- **ORM**: TypeORM para la gestión de entidades, migraciones y seeders.
- **Infraestructura**: 
  - Configuración modular para facilitar la escalabilidad.
  - Comunicación segura con la blockchain para operaciones específicas.
- **Servicios implementados**:
  - Autenticación y autorización basada en roles.
  - Gestión de usuarios, roles y wallets.
  - Funciones específicas para la interacción con contratos inteligentes.

## Estructura del Proyecto

### 1. Smart Contracts
Repositorio: [Smart Contracts](https://github.com/eco-tienda-org/Smart-Contracts.git)

Este módulo contiene los contratos inteligentes que definen el sistema de recompensas en tokens, así como las funciones para interactuar con la tienda. Principales funcionalidades:
- Creación y distribución de tokens.
- Airdrop de tokens para incentivar la participación.
- Registro y seguimiento de transacciones relacionadas con la compra de ropa.

### 2. Frontend
Repositorio: [Demo Frontend EcoTienda](https://github.com/eco-tienda-org/DemoFrontendEcoTienda.git)

El frontend es una aplicación web moderna diseñada para ofrecer una experiencia de usuario intuitiva y accesible. Funcionalidades principales:
- Registro e inicio de sesión con MetaMask.
- Exploración de productos disponibles en la tienda.
- Interacción con los contratos inteligentes para realizar compras y recibir tokens.
- Panel de usuario para consultar el saldo de tokens y el historial de transacciones.

### 3. Backend
Repositorio: [Servidor EcoTienda](https://github.com/eco-tienda-org/Servidor-EcoTienda.git)

El backend actúa como intermediario entre el frontend, la base de datos y la blockchain. Principales funcionalidades:
- Gestión de usuarios y roles.
- Sincronización de datos entre la base de datos y la blockchain.
- Control y seguridad en las interacciones con los contratos inteligentes.
- Servicios REST para las operaciones del frontend.

## Equipo de Desarrollo

- [Alexander](https://github.com/Alexcripto369)
- [Andrés Chanchi](https://github.com/AndresChanchi/)
- [Irma](https://github.com/ramigaririg)
