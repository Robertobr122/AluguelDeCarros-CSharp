# Sistema de Locadora de Veículos - AluCar 🚗

### **Descrição**

Sistema desenvolvido em **C#** para o gerenciamento de uma locadora de veículos, permitindo o cadastro de clientes e veículos, além da realização de reservas. O projeto é um exercício prático que explora conceitos de **Programação Orientada a Objetos (POO)**, como herança e polimorfismo, e inclui validações robustas de dados.

---

### **Funcionalidades Principais ⚙️**

- **Cadastro de Clientes**: Com validação de nome, idade mínima (21 anos) e categoria de CNH (`A`, `B` ou `C`).
- **Cadastro de Veículos**: Suporte a diferentes tipos de veículos (`Carro`, `Moto`, `Caminhao`), cada um com suas regras de diária base e requisitos de CNH.
- **Sistema de Reservas**:
  - Validação de CNH compatível com o veículo.
  - Cálculo de diárias com descontos progressivos.
  - Opção de adicionar condutor adicional.
  - Registro de quilometragem inicial e final.
  - Controle de status da reserva (`Pendente`, `Confirmada`, `Cancelada`, `Finalizada`).

---

### **Regras de Negócio 📋**

- **Descontos e Taxas**:
  - **Carros**: **5%** de desconto para locações a partir de 5 dias e **10%** para 10 dias ou mais.
  - **Motos**: **15%** de desconto fixo sobre a diária.
  - **Caminhões**: **15%** de acréscimo fixo sobre a diária.

- **Requisitos de Locação**:
  - Idade mínima de **21 anos**.
  - **CNH compatível** com o veículo escolhido.
  - Período de locação: **mínimo de 1 dia** e **máximo de 30 dias**.

---

### **Tecnologias Utilizadas 🛠️**

- **C#**: Linguagem de programação.
- **.NET Core**: Framework de desenvolvimento.
- **Programação Orientada a Objetos**: Utilização de classes, herança e polimorfismo.
- **Tratamento de Exceções**: Para garantir a robustez do sistema.
- **Regex**: Para validação de formatos de dados.

---

### **Como Executar 🚀**

1.  Clone o repositório:
    `git clone https://github.com/Robertobr122/AluguelDeCarros-CSharp.git`

2.  Navegue até o diretório do projeto:
    `cd AluguelDeCarros-CSharp`

3.  Execute a aplicação:
    `dotnet run`

---

### **Contribuição 🤝**

Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novas funcionalidades. Para isso, por favor, abra uma _issue_ para discussão e, em seguida, envie um _Pull Request_.

---

### **Licença 📝**

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT).