# Desafio "Explorando os Recursos de IA Generativa com Copilot e OpenAI"

##### Como parte da resolução do desafio proposto pela DIO, será descrito neste documento as etapas de como foi realizado o uso da ferramenta Microsoft Copilot, como parte da utilização de ferramentas com IA Generativa.

##### Os passos seguidos foram:

###### 1. Foi acessado o Portal do Microsoft Copilot (https://copilot.microsoft.com/)
###### 2. Após acessar o Site, foi inserida as credenciais da Conta Microsoft, para poder acessar a ferramenta.

![home](https://github.com/dmtz1989/desafioMicrosoftCopilotDIO/blob/main/output/home.png)
###### 3. Como primeiro Input no Copilot, foi realizada a seguinte pergunta:

    Boa noite. Gostaria de 5 indicações para um passeio gastronômico em Recife

###### 3.1. Foi retornado para mim a seguinte Resposta:

![output1](https://github.com/dmtz1989/desafioMicrosoftCopilotDIO/blob/main/output/output%201.png)

###### 3.2. Baseado na resposta dada, verifiquei que os locais realmente existem, mas possuindo uma falha em um dos endereços citados. Com essa informação em mãos, o correto a fazer é informar sobre o erro e treinar novamente a IA com o endereço correto, para evitar futuros erros.

###### 4. O Segundo Input no Copilot, foi solicitando a criação de uma imagem com as seguintes características:
    
    Gostaria que você gerasse uma Imagem de uma senhora aproveitando uma sobremesa em um restaurante com uma sacada a beira-mar a noite

###### 4.1. O output que tive foi o seguinte:

![output2](https://github.com/dmtz1989/desafioMicrosoftCopilotDIO/blob/main/output/output%202.png)
    
###### 4.2. Baseado nas imagens geradas, achei satisfatório, pois possuiu uma diversidade de ambientes, como também de pessoas de traços etnicos diferentes para a resposta, como também a imagem gerada ser de bastante qualidade.

###### 5. Por fim, solicitei ajuda ao Copilot para criar sistema em Python, com o seguinte input:

    Me ajuda a criar um sistema de roladores de dados de RPG usando python

###### 5.1. Como resultado, o seguinte output foi gerado:

# Programa para rolar dados de RPG

    import random
    
    def rolar_dado(lados):
        """
        Função para rolar um dado com o número especificado de lados.
        :param lados: Número de lados do dado
        :return: Resultado do lançamento
        """
        return random.randint(1, lados)
    
    def main():
        print("Bem-vindo ao Rolador de Dados de RPG!")
        while True:
            try:
                num_lados = int(input("Digite o número de lados do dado (6, 12, 16 ou 20): "))
                if num_lados not in [6, 12, 16, 20]:
                    print("Por favor, escolha um número válido de lados.")
                    continue
                resultado = rolar_dado(num_lados)
                print(f"Você rolou um dado de {num_lados} lados e obteve o resultado: {resultado}")
            except ValueError:
                print("Entrada inválida. Digite um número inteiro.")
            novamente = input("Deseja rolar novamente? (s/n): ")
            if novamente.lower() != "s":
                break
    
    if __name__ == "__main__":
        main()
        
![output3](https://github.com/dmtz1989/desafioMicrosoftCopilotDIO/blob/main/output/output%203.png)

###### 5.2. Após os testes no código e na leitura do código, achei o código interessante. Adicionaria mais algumas funcionalidades, como quantidade de dados, adição de dificuldade nos dados, como também adição ou redução de valores aos resultados, como também soma de resultados nos dados rolados.

###### 6. Diante dos resultados gerados pelo Copilot, concluo que o potencial para uso da ferramenta é vasto, principalmente para quem consegue dominar e fazer os questionamentos corretos para a IA, conseguindo assim extrair o melhor que a ferramenta possa oferecer para seus usuários.
    
