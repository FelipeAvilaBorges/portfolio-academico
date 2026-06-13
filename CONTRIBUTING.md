# Guia de Contribuição

Obrigado pelo interesse em contribuir com este repositório! Embora seja um 
projeto de portfólio pessoal/acadêmico, ele segue um fluxo de trabalho 
baseado em boas práticas de colaboração com Git e GitHub.

## Estrutura do repositório

- `projetos-academicos/` — projetos desenvolvidos durante o curso;
- `projetos-academicos/projetos-pessoais/` — projetos desenvolvidos por 
  iniciativa própria;
- `documentacao/` — documentação geral e materiais de apoio.

## Fluxo de branches

- `main` — branch principal, protegida. Representa a versão publicada 
  (produção) do portfólio no GitHub Pages;
- `feature/nome-da-alteracao` — branches criadas para desenvolver novas 
  funcionalidades, correções ou atualizações de conteúdo.

## Como contribuir

1. Crie uma nova branch a partir da `main`:
```bash
   git checkout -b feature/nome-da-alteracao
```
2. Faça as alterações necessárias.
3. Use mensagens de commit claras e padronizadas, seguindo o padrão:
   - `feat:` para novas funcionalidades;
   - `fix:` para correções;
   - `docs:` para alterações na documentação;
   - `chore:` para tarefas de manutenção.

   Exemplo:
```bash
   git commit -m "feat: adiciona novo projeto pessoal ao portfólio"
```
4. Envie a branch para o repositório remoto:
```bash
   git push origin feature/nome-da-alteracao
```
5. Abra um **Pull Request** para a branch `main`, descrevendo as alterações 
   realizadas.
6. Aguarde a revisão antes do merge (a branch `main` é protegida e exige 
   Pull Request).

## Padrões de código

- Utilize HTML e CSS organizados e comentados quando necessário;
- Mantenha a estrutura de pastas existente ao adicionar novos projetos;
- Cada novo projeto deve conter um `README.md` próprio, descrevendo objetivo, 
  tecnologias utilizadas e instruções de acesso/demo.

## Dúvidas

Em caso de dúvidas, abra uma Issue descrevendo a situação.
