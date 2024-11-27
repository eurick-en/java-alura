<h1 align="center">💳 Sistema Bancário em Java</h1>

<p align="center">
  Este é um projeto simples de sistema bancário desenvolvido durante o curso de <strong>Java</strong> na <a href="https://www.alura.com.br" target="_blank">Alura</a>. O objetivo é aplicar conceitos fundamentais da linguagem, como estruturas de controle, manipulação de entrada do usuário e operações matemáticas.
</p>

---

## 🛠️ Funcionalidades

<ul>
  <li><strong>Consultar Saldo:</strong> Exibe o saldo atual do cliente.</li>
  <li><strong>Transferir Valor:</strong> Permite transferências, com verificação de saldo suficiente.</li>
  <li><strong>Receber Valor:</strong> Atualiza o saldo ao receber depósitos.</li>
  <li><strong>Sair:</strong> Finaliza o programa.</li>
</ul>

---

## 📂 Estrutura do Projeto

<p>O projeto é composto por um único arquivo Java:</p>

<pre>
Desafio.java
</pre>

### 📜 Código Principal

```java
// Exemplo de trecho de código
if (opcao == 1) {
    System.out.println("O saldo atualizado é " + saldo);
} else if (opcao == 2) {
    System.out.println("Qual o valor que deseja transferir?");
    double valor = leitura.nextDouble();
    if (valor > saldo) {
        System.out.println("Não há saldo para realizar a transferência.");
    } else {
        saldo -= valor;
        System.out.println("Novo saldo: " + saldo);
    }
}
