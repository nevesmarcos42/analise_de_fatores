# Análise de Fatores no Conjunto de Dados Iris

## Descrição
Este projeto realiza uma análise de fatores no conjunto de dados **Iris**, utilizando técnicas estatísticas e de aprendizado de máquina para explorar padrões e estrutura dos dados.

## Tecnologias Utilizadas
- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

## Análises Realizadas
1. **Análise de Componentes Principais (PCA)**: Redução da dimensionalidade para melhor compreensão da variabilidade dos dados.
2. **Detecção de Outliers**: Utilização de boxplots, método de Tukey e o algoritmo DBSCAN para identificar observações atípicas.
3. **Clusterização com K-Means**: Agrupamento das amostras em três clusters correspondentes às espécies reais do conjunto de dados.

## Resultados
- A PCA demonstrou que poucos componentes principais conseguem explicar grande parte da variabilidade dos dados.
- O DBSCAN identificou observações consideradas outliers com base na distribuição das variáveis.
- O K-Means obteve resultados coerentes com a classificação original das espécies, embora algumas observações tenham sido classificadas de forma diferente.

## Como Executar
1. Instale as dependências necessárias utilizando:
   ```bash
   pip install pandas seaborn matplotlib scikit-learn
   ```
2. Execute o notebook **Análise_de_fatores_no_conjunto_de_dados_Iris.ipynb** em um ambiente Jupyter Notebook.

## Criando um Repositório no GitHub
1. Acesse [GitHub](https://github.com/) e faça login.
2. Clique no botão **New** para criar um novo repositório.
3. Defina um nome para o repositório, adicione uma descrição e escolha se será público ou privado.
4. Inicialize o repositório com um README ou faça isso manualmente depois.
5. No terminal, clone o repositório com:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
6. Navegue até a pasta do projeto e adicione os arquivos:
   ```bash
   cd nome-do-repositorio
   git add .
   git commit -m "Primeiro commit"
   git push origin main
   ```

📝 Uso
Para utilizar o projeto, carregue o dataset, execute o script principal e visualize os resultados gerados. Você pode ajustar os hiperparâmetros e modelos conforme necessário.

🌟 Contribuições
Contribuições são bem-vindas! Se você tiver sugestões, correções ou melhorias, sinta-se à vontade para abrir issues e enviar pull requests.

📜 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

📞 Contato
Para mais informações, entre em contato:

Email: nevesmarcos42@gmail.com

LinkedIn: linkedin.com/in/nevesmarcos

Obrigado por conferir este projeto! Se você achou interessante, deixe uma estrela no repositório e compartilhe com seus colegas. 🚀✨

