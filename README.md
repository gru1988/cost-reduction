# cost-reduction — VitaStore: оптимизация операционных затрат

Проектная работа: снижение TCO магазинов сети VitaStore за счёт перехода в облако и автоматизация онбординга купленных магазинов.

| Директория | Задание | Файлы |
|---|---|---|
| `Task1` | Карта бизнес-возможностей и матрица Buy vs Build | `capability_map_heatmap.png` — карта с heatmap; `sourcing_quadrant.png` — матрица Sourcing Strategy (визуально); `sourcing_matrix.xlsx` / `sourcing_matrix.md` — матрица с обоснованием |
| `Task2` | TO-BE процесс онбординга магазина (BPMN + Automation) | `onboarding_to_be.bpmn` — BPMN 2.0; `onboarding_to_be.png` — диаграмма; `verification_point.md` — точка верификации и участие человека |
| `Task3` | Целевая облачная архитектура | `c4_as_is_containers.png` — AS-IS (C4, Containers); `hld_to_be_cloud_pos.png` — HLD с HAL / Payment Gateway; `offline_sync.md` — офлайн-режим и синхронизация |
| `Task4` | TCO Analysis | `tco_analysis.xlsx` — расчёт TCO на 3 года для 100 магазинов; `tco_conclusion.md` — вывод о ROI и сроке окупаемости |

## Ключевые результаты

- Онбординг магазина: **2–3 недели → ≤ 5 рабочих дней**. ИИ-маппинг автоматически сопоставляет около 85% SKU, человек проверяет только спорные позиции.
- Магазин: **без локального сервера**. Web POS на планшете + HAL Agent + ККТ, продажа за наличные с фискальным чеком работает офлайн.
- TCO инфраструктуры: **−45% в устойчивом режиме**, окупаемость **≈ 18 месяцев**, экономия **≈ 39 млн ₽** за 3 года на 100 магазинов.
