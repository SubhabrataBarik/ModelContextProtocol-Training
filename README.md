git init
git branch -M main
echo .env >> .gitignore
git add .
git commit -m "Initial commit - cleaned repo"
git remote add origin https://github.com/SubhabrataBarik/ModelContextProtocol-Training.git
git push -u origin main --force


git branch
git branch feature-x
git branch
git checkout feature-x
git branch

git checkout main
git switch main
git pull origin main
git merge feature-x
git push origin main
git branch -d feature-x




| Server        | Install Command                                                                        |
| ------------- | -------------------------------------------------------------------------------------- |
| DuckDuckGo    | `npx duckduckgo-mcp-server`                                                            |
| Google Search | `npx @mcp-server/google-search-mcp@latest`                                             | DONE
| Wikipedia     | `npx wikipedia-mcp-server`                                                             | DONE
| Playwright    | `npm install -g @playwright/test`                                                      | DONE
| Airbnb        | `npx @openbnb/mcp-server-airbnb`                                                       | DONE
| GitHub        | `npx -y @modelcontextprotocol/server-github`                                           | DONE
| Git           | `uvx mcp-server-git --repository path/to/your/repo`                                    | DONE
| Filesystem    | `npx -y @modelcontextprotocol/server-filesystem /allowed/path`                         | DONE
| Postgres      | `npx -y @modelcontextprotocol/server-postgres postgresql://user:pass@localhost/dbname` | DONE
| Memory        | `npx -y @modelcontextprotocol/server-memory`                                           | DONE



.env
OPENAI_API_KEY = ""

LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT='https://api.smith.langchain.com'
LANGCHAIN_API_KEY=''
LANGCHAIN_PROJECT='ModelContextProtocol'

GITHUB_PERSONAL_ACCESS_TOKEN=""
# Example [https://www.googleapis.com/customsearch/v1?key=GOOGLE_API_KEY=GOOGLE_CSE_ID&q=what+is+minecraft]
GOOGLE_API_KEY=""
GOOGLE_CSE_ID=""