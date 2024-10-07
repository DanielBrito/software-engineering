# Monitoring - Evaluate Your Microservice

Considere utilizar este template como referência ao avaliar um novo microsserviço.

## Key Metrics

- Quais são as principais métricas de negócio deste microsserviço?
- Quais são as principais métricas de infraestrutura deste microsserviço?
- Todas as métricas-chave deste microsserviço são monitoradas?

## Logging

- Quais informações este microsserviço precisa logar?
- Este microsserviço loga todas as requests importantes?
- O log reflete com precisão o estado do microsserviço em um determinado momento?
- Esta solução de log é econômica e escalável?

## Dashboards

- Este microsserviço tem um dashboard?
- O dashboard é fácil de interpretar? 
- Todas as métricas principais são exibidas no dashboard?
- Posso determinar se este microsserviço está funcionando corretamente ou não observando o dashboard?

## Alertas

- Existe um alerta para cada métrica-chave?
- Todos os alertas são definidos por bons thresholds?
- Os thresholds de alerta estão definidos adequadamente para que os alertas sejam disparados antes que ocorra uma quebra da aplicação?
- Todos os alertas são acionáveis?
- Há instruções de passo a passo para triagem, mitigação e resolução para cada alerta no runbook de on-call?

## On-call

- Há uma rotação definida para monitorar este microsserviço?
- Há um mínimo de duas pessoas em cada turno de on-call?
- Há procedimentos de on-call padronizados em toda a organização de engenharia?
