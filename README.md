## Manan Patel

Machine learning · data science · analytics · data engineering
MS Computer Science, Northeastern University '26 · Boston

I work across the whole data stack — from the pipeline that lands the data to the model, the experiment, and the decision at the end. Portfolio: **[mananpatel25.github.io](https://mananpatel25.github.io)**

### Machine learning
| | | |
|---|---|---|
| [Heart rate from a webcam](https://github.com/Mananpatel25/CS6983) | Real-time rPPG: face detection → FFT → calibration → live GUI; PhysNet / RTrPPG 3D CNNs. **7.2 bpm MAE**, 58% error cut after calibration. | PyTorch · OpenCV |
| [CLEF 2025 species benchmark](https://github.com/Mananpatel25/prcv_final_collab) | DenseNet-121 vs Inception v3 vs custom CNN on Animal/Plant/FungiCLEF. **99.1%** AnimalCLEF, 2,427 classes. | PyTorch · TensorFlow |
| [Retinal disease from OCT](https://github.com/Mananpatel25/Retina-damage-classification-from-oct-images) | Transfer learning on 84K OCT scans, 4 classes. **96.3%** test accuracy. | TensorFlow |
| [Crowd line-crossing counter](https://github.com/Mananpatel25/Flexible-Vision-Based-Crowd-Monitoring) | Draw any line on a video; Faster R-CNN + centroid tracking counts crossings. | PyTorch · OpenCV |
| [Posture detection on Arduino](https://github.com/Mananpatel25/Detecting-Postures-using-TFlLite-and-Arduino-on-Hardware) | IMU → Keras → TFLite on a Nano 33 BLE, 5 postures, **92.7%** val. | TFLite · Arduino |

### Data science
| | | |
|---|---|---|
| [Prime Plot](https://github.com/Mananpatel25/prime-plot) | Where should a business open? Voronoi city simulation + XGBoost (**87%**) + LLM agents that explain the pick. | XGBoost · LangGraph |
| [Walmart sales forecasting](https://github.com/Mananpatel25/Time-Series-Forecasting-of-Sales-at-Walmart-Superstores) | Tree ensembles with calendar features vs auto-ARIMA. Feature selection cut WMAE **5,850 → 1,801**. | scikit-learn · statsmodels |
| [Plant leaf disease, deployed](https://github.com/Mananpatel25/Plant-leaf-disease-classification-on-streamlit) | InceptionV3 / Xception / VGG on 14K PlantVillage images, served in Streamlit. **98.0%** Xception. | Keras · Streamlit |

### Analytics
| | | |
|---|---|---|
| [Experimentation engine](https://github.com/Mananpatel25/experimentation-engine) | A/B testing library: power, CUPED, mSPRT sequential, Bayesian, segment HTE. Validated on **13.9M** Criteo users; ends in a ship/no-ship memo. | SciPy · Statsmodels |
| [Sentiment → stock returns](https://huggingface.co/spaces/hscarminati/sentiment-stock-dashboard) | 100K+ posts × prices across VADER/FinBERT/NRC; which signals predict 1/7/30-day returns. Live app. | FinBERT · Shiny |

### Data engineering
| | | |
|---|---|---|
| [MBTA real-time lakehouse](https://github.com/Mananpatel25/mbta-lakehouse) | Kafka → event-time Parquet on S3 → dbt → Airflow. Idempotent writes, late-arrival handling, SCD2, quality gates, CI. One `docker compose up`. | Kafka · Airflow · dbt · DuckDB |
| [CodeCartographer](https://github.com/Mananpatel25/codecartographer) | Static-analysis CLI: dependency graph, circular imports, god modules, LLM Q&A over graph facts. Tested. | Python · Typer |

### Experience
- **KeelWorks** (2026) — data engineer: Airflow/dbt pipelines into S3, quality gates, CI/CD to AWS
- **Northeastern University** (2025–26) — research data engineer, 100GB+ hydrophone audio → 93% species classifier, published
- **GetOnData Solutions** (2023–24) — PySpark/Airflow ETL into Snowflake, ML serving on AWS

📫 manrp2625@gmail.com
