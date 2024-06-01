# Quantidade de pessoas em cada faixa etária
idades = ['18 a 26 anos', 'Mais de 50 Anos', '36 a 49 Anos', '27 a 35 Anos']
quantidades = [6, 81, 168, 51]

# Criando o gráfico de pizza
plt.figure(figsize=(8, 8))
plt.pie(quantidades, labels=idades, autopct='%1.1f%%', startangle=140)
plt.title('Distribuição de Idades')
plt.axis('equal')  # Deixa o gráfico de pizza circular
plt.show()
