[README.md](https://github.com/user-attachments/files/25614364/README.md)
# 🛠 Sistema de Controle de Preventivas

Sistema desktop desenvolvido em Python para controle de manutenções
preventivas de máquinas industriais.

O sistema importa preventivas pendentes a partir de um arquivo Excel,
permite que técnicos realizem login com ID e nome, finalizem preventivas
e mantenham histórico completo de auditoria.

------------------------------------------------------------------------

## 🚀 Funcionalidades

-   🔐 Sistema de Login com ID e Nome
-   📥 Importação automática de preventivas pendentes via Excel
-   📋 Visualização de preventivas pendentes
-   ✅ Finalização individual de preventivas
-   🗂 Histórico de preventivas fechadas
-   🧾 Registro de auditoria (ID e nome de quem finalizou)
-   🗄 Banco de dados SQLite para armazenamento das preventivas
    realizadas
-   📦 Geração de executável (.exe) com PyInstaller

------------------------------------------------------------------------

## 🧩 Tecnologias Utilizadas

-   Python 3
-   Tkinter (Interface Gráfica)
-   SQLite
-   OpenPyXL (manipulação de Excel)
-   Pandas
-   PyInstaller

------------------------------------------------------------------------

## 🏗 Estrutura do Projeto

    controle_preventivas/
    │
    ├── main.py
    ├── banco.py
    ├── tela_login.py
    ├── tela_painel.py
    ├── excel_manager.py
    ├── maquinas.xlsx
    └── icone.ico

------------------------------------------------------------------------

## ⚙️ Como Executar

1.  Instale as dependências:

    pip install pandas openpyxl

2.  Execute o projeto:

    SCA.exe

------------------------------------------------------------------------

## 🖥 Gerar Executável

    python -m PyInstaller --onefile --windowed --icon=icone.ico main.py

O executável será criado dentro da pasta `dist`.

------------------------------------------------------------------------

## 🎯 Objetivo do Projeto

Digitalizar e automatizar o controle de manutenções preventivas,
eliminando erros manuais em planilhas e garantindo rastreabilidade
completa das atividades realizadas.

------------------------------------------------------------------------

## 📌 Próximas Melhorias

-   Controle de níveis de acesso (Técnico / Gerente)
-   Relatórios em PDF
-   Integração com servidor em rede
-   Dashboard com indicadores
-   Sistema multiusuário corporativo

------------------------------------------------------------------------

## 👨‍💻 Autor

Desenvolvido por Pablo Pellozzo\
Técnico em Automação Industrial\
Estudante de Ciência da Computação
