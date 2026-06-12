# 🧮 Calculo

![Shell Script](https://img.shields.io/badge/Language-Shell_Script-green)
![Status](https://img.shields.io/badge/Status-Ativo-success)

Bem-vindo ao repositório **Calculo**! Este projeto contém um conjunto de scripts desenvolvidos para auxiliar na resolução de problemas matemáticos e na realização de cálculos automatizados diretamente pelo terminal.

---

## 📋 Pré-requisitos

Para que os scripts funcionem corretamente, é **obrigatório** ter a calculadora `bc` (Basic Calculator) instalada no seu sistema Linux/Unix. Ela é utilizada para lidar com cálculos matemáticos avançados e números decimais dentro dos scripts.

**Como instalar o `bc`:**

- **Debian / Ubuntu / Linux Mint:**
  ```bash
  sudo apt-get update
  sudo apt-get install bc
  ```
- **Arch Linux / Manjaro:**
  ```bash
  sudo pacman -S bc
  ```
- **Fedora / RHEL / CentOS:**
  ```bash
  sudo dnf install bc
  ```

---

## 🚀 Scripts Disponíveis

Atualmente, o repositório conta com os seguintes utilitários:

### 1. Par ordenado (`Par ordenado.sh`)
Um script interativo em Shell Script (baseado em uma ideia original em Java e recriado por XayUp) que permite definir elementos para dois conjuntos (X e Y) e gerar o **Produto Cartesiano** (pares ordenados) entre eles. 
- **Funcionalidades:** Menu interativo para definir valores das variáveis, gerenciar (deletar) e listar os pares ordenados criados.

### 2. Equação de segundo grau (`Equação de segundo grau/`)
Scripts focados na resolução de equações polinomiais do 2º grau (do tipo `ax² + bx + c = 0`), ideal para calcular o delta e encontrar as raízes (x' e x'') utilizando a fórmula de Bhaskara.

---

## 💻 Como utilizar

1. **Clone o repositório para sua máquina:**
   ```bash
   git clone https://github.com/Griff-OFC/Calculo.git
   cd Calculo
   ```

2. **Dê permissão de execução** para o script que você deseja rodar (por exemplo, o de pares ordenados):
   ```bash
   chmod +x "Par ordenado.sh"
   ```

3. **Execute o script no terminal:**
   ```bash
   ./"Par ordenado.sh"
   ```

*(Siga o mesmo processo para executar os scripts da pasta de equação do segundo grau, lembrando de navegar até o diretório ou passar o caminho correto).*

---

## 🤝 Contribuições

Sinta-se à vontade para contribuir com este projeto! Você pode:
- Reportar problemas ou dar sugestões abrindo uma **Issue**.
- Melhorar o código ou adicionar novos scripts matemáticos através de um **Pull Request**.

---
*Desenvolvido com 💡 por **[Griff-OFC](https://github.com/Griff-OFC)**.*
