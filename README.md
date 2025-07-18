# Repórter de Notícias Paulistano (Agente de IA)

Este projeto implementa um agente de inteligência artificial que atua como um repórter de notícias com uma personalidade marcante e um estilo paulistano autêntico. Utilizando o framework `Agno` e o modelo `Google Gemini`, o agente é instruído a criar manchetes chamativas, compartilhar notícias com entusiasmo e sotaque paulistano, usar gírias locais e encerrar com uma frase de efeito, sempre em português-br.

## Visão Geral

A criação de agentes de IA com personas e estilos de comunicação específicos é uma tendência crescente. Este projeto demonstra como o framework `Agno` facilita essa modelagem, permitindo que o LLM (`gemini-2.5-flash`) adote um papel de "repórter entusiasmado com um toque paulistano". Isso é alcançado através de um conjunto detalhado de instruções (`instructions`) que guiam o comportamento e a saída do agente.

**Características do Repórter Paulistano:**
* **Manchetes Chamativas:** Inicia com emojis e um título que prende a atenção.
* **Atitude Paulistana:** Linguagem descontraída e cheia de energia.
* **Conciso e Divertido:** Respostas diretas, mas com um toque de humor.
* **Referências Locais:** Inclusão de menções a lugares ou gírias de São Paulo.
* **Despedida Cativante:** Encerra com uma frase de efeito característica de repórteres.
* **Idioma:** Respostas sempre em português-br.

## Estrutura do Projeto

* `agent.py`: O script Python principal que define o agente e suas instruções.

## Tecnologias Utilizadas

* **Python 3**
* **Agno**: Framework para construir agentes de IA.
    * `agno.agent.Agent`: Classe base para o agente.
    * `agno.models.google.Gemini`: Conector para modelos Gemini.
* **Google Gemini API**: Para o modelo de linguagem (`gemini-2.5-flash`).

## Exemplo de uso

<img width="1590" height="531" alt="Image" src="https://github.com/user-attachments/assets/79b0fc2c-99cd-4acc-a528-9eb407511eeb" />
