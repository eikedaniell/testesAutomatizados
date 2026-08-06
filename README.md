## Sobre

Este projeto foi criado para verificar automaticamente se um sistema está funcionando corretamente.

Em vez de uma pessoa precisar testar tudo manualmente, o programa realiza essas verificações sozinho. Ele confere se as informações são enviadas e recebidas corretamente e também simula ações de um usuário, como abrir páginas, clicar em botões e preencher formulários.

Dessa forma, é possível encontrar erros mais rapidamente e garantir que o sistema continue funcionando mesmo após receber novas atualizações. Para isso, o projeto utiliza Python e ferramentas de automação de testes que executam essas verificações de forma rápida e confiável.

## Tecnologias
> Python, Pytest, Requests, Selenium, GitHub Actions

## Instalação e execução

### API
```bash
cd api-tests
pip install -r requirements.txt
pytest tests/ -v
```

### Web

```bash
cd web-tests
pip install -r requirements.txt
pytest tests/ -v
```

## Testes de API executando localmente

<img width="1445" height="291" alt="Captura de tela 2026-05-28 164624" src="https://github.com/user-attachments/assets/24d6f32b-3529-4006-a950-43561bf7d2be" />

## Testes Web executando localmente

<img width="1458" height="264" alt="Captura de tela 2026-05-28 164543" src="https://github.com/user-attachments/assets/498d82ec-d42c-443d-adda-b989236c26ca" />

## Pipelines no Github Actions

<img width="1315" height="120" alt="Captura de tela 2026-05-28 164956" src="https://github.com/user-attachments/assets/f12918cc-4a8d-40d4-82db-4f0518137d59" />








