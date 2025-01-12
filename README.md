
# DIO | Resumos Git e GitHub

Repositório para armazenar recursos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub [Digital Innovation One](https://web.dio.me/).

## 📄 Documentação 
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/pt)

## Resumos das Aulas
| Aulas | Resumos |
|-------|---------|
| Versionamento | [Link](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?autoplay=1&back=%2Ftrack%2Fcoding-the-future-heineken-ia-para-analise-de-dados)

## Repositório
| Git | Função |
|-----|--------|
| gitignore | ignorar um rep. |
| gitkeep | guardar informações (vazias ou não) |

## 📜 Comandos 
| Função | Comando | 
|--------| --------|
| Inicializar Git | git init |
| Verificar Status | git Status |
| Add | git add <file> |
| Add (todos) | git add . |
| Commit (-m -> add msg) | git commit -m |
| Log (vizualizar alterações) | git log |
| Reflog (detalhado) | git reflog |
| Remover .git | rm -rf .git |
| Restaurar | git restore <file> |
| Alterar mensagem do commit | git commit --amend -m"" |
| Alt msg via editor | git commit --amend |
| Mudar commit de base, preservar alt para novo commit | git reset --soft <ID> |
| Desfazer o staging de arq., precisa das alt para fazer ajustes/commits | git reset --mixed <ID> |
| Descartar completamente todas alt. e reverter o branch para commit especificado | git reset --hard <ID> |
