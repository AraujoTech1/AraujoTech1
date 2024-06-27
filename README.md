import markdown

# Ler o conteúdo do arquivo README.md
with open('README.md', 'r', encoding='utf-8') as file:
    markdown_text = file.read()

# Converter Markdown para HTML
html = markdown.markdown(markdown_text)

# Adicionar estilos às palavras específicas
html = html.replace('**tecnologia**', '<span style="color:lightblue; font-weight:bold;">tecnologia</span>')
html = html.replace('Cloud', '<span style="color:lightblue;">Cloud</span>')

# Salvar o HTML resultante em um arquivo
with open('README.html', 'w', encoding='utf-8') as file:
    file.write(html)

print("Conversão concluída e salva em README.html")
