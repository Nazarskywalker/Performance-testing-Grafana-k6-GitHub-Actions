# Проєкт: Performance testing із Grafana k6 + GitHub Actions

## Що включено
- `test.js` — робочий сценарій навантажувального тесту.
- `.github/workflows/k6-local.yml` — запуск локального тесту на GitHub Actions.
- `.github/workflows/k6-cloud.yml` — надсилання результатів у Grafana Cloud.

## Як використовувати
1. Створи репозиторій на GitHub.
2. Завантаж файли з цього архіву.
3. У `Settings → Secrets → Actions` додай:
   - `K6_CLOUD_TOKEN`
   - `K6_CLOUD_PROJECT_ID`
4. Відправ push — GitHub автоматично запустить тести.
