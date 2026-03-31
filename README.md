# Berthax Surgical - Sistema de Inspeção de Qualidade

Este é um sistema web para inspeção de qualidade desenvolvido para a Berthax Surgical LTDA. Permite gerenciar ordens de serviço (OS), registrar não conformidades, gerar relatórios em PDF e muito mais.

## Funcionalidades

- **Login de Usuários**: Autenticação via Supabase para rastrear usuários conectados.
- **Dashboard**: Visão geral com estatísticas de conformidade.
- **Histórico de Inspeções**: Lista e busca de ordens de serviço.
- **Criação de OS**: Formulário para registrar novas inspeções com itens, técnicos e observações.
- **Não Conformidades**: Registro de problemas com fotos, severidade e responsáveis.
- **Exportação**: Geração de PDFs e envio por e-mail.
- **Importação**: Carregar dados de planilhas Excel.
- **Configurações**: Tema escuro/claro, idioma (PT/EN/ES), armazenamento local.
- **Armazenamento**: Dados salvos localmente como JSON ou no Supabase.

## Tecnologias Utilizadas

- **React**: Framework JavaScript para a interface.
- **Supabase**: Banco de dados e autenticação.
- **Chart.js**: Gráficos no dashboard.
- **XLSX**: Manipulação de planilhas Excel.
- **PDF.js** (implícito): Geração de PDFs.
- **Babel**: Transpilação JSX.

## Como Usar

1. Abra o arquivo `index.html` em um navegador moderno.
2. Faça login com seu nome.
3. Navegue pelo dashboard, crie novas inspeções, etc.

### Configuração do Supabase

Para usar o banco de dados:

1. Crie uma conta no [Supabase](https://supabase.com).
2. Crie um novo projeto.
3. Execute o SQL fornecido no código para criar a tabela `usuarios_conectados`.
4. Substitua as chaves `SUPABASE_URL` e `SUPABASE_KEY` no código.

**Atenção**: As chaves atuais são de exemplo e devem ser substituídas por suas próprias para segurança.

## Instalação (Opcional para Desenvolvimento)

Se quiser desenvolver localmente:

1. Clone o repositório.
2. Instale dependências (se houver package.json).
3. Abra o HTML em um servidor local para evitar problemas de CORS.

## Contribuição

Este projeto é para fins educacionais. Sinta-se à vontade para contribuir com melhorias.

## Licença

MIT License - veja o arquivo LICENSE.

## Autor

Josias Nogueira - Estudante de Desenvolvimento Web</content>
<parameter name="filePath">c:\Users\User\Downloads\Berthax 200\README.md