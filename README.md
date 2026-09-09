## Shah Hussain

Data engineer based in Nottingham, UK. I work on the ingestion side of data platforms: getting messy data out of the web and out of APIs at volume, validating it, and landing it somewhere a team can actually trust.

Four years of that was at Arbisoft on StyleSage, a fashion intelligence platform whose parent was acquired by Centric Software. I owned the ingestion layer: a fleet of 600+ Scrapy spiders pulling pricing and product data off hundreds of retailer sites, held at around 99.5% uptime. The hard part was never writing one scraper. It was keeping several hundred of them alive while the sites underneath kept changing. I put schema checks, deduplication and completeness validation through the pipeline so the analytics team stopped losing days to cleanup. Promoted to Senior Software Engineer in 2024.

Alongside that I have freelanced on Fiverr and Upwork since 2019, 200+ projects for clients across the US, UK, Australia and Europe. I finished an MSc in Data Science at the University of Surrey in 2026.

### Selected work

**[spatial-auto-annotation](https://github.com/shah-arbisoft/spatial-auto-annotation)**
My MSc dissertation. Give it a raw RGB image and it detects objects, segments them, estimates monocular depth, lifts each object into 3D, then computes the seven spatial predicates between every ordered pair from the geometry. No human decides a label anywhere in the chain. Exports scene graphs as Visual Genome JSON, YOLO txt and h5. Dockerised, config driven, with tests and an eval harness.

**[robot-factcheck](https://github.com/shah-arbisoft/robot-factcheck)**
The validation half of the dissertation. A small web game that crowd-checks the annotator against a stratified sample of roughly 2,000 claims, drawn specifically from object pairs no human ever labelled. That is the part with no ground truth, which is exactly where you want to know whether the tool holds up.

**[COMM061-PG29](https://github.com/shah-arbisoft/COMM061-PG29)**
MSc NLP coursework. Sequence classification for sentiment and sarcasm across Australian, Indian and British English, using the BESSTIE dataset. Sarcasm is the interesting half: the surface sentiment of a sarcastic sentence usually points the opposite way to what the writer means, so a model tuned only for sentiment gets confidently wrong answers.

### What I work with

**Languages** Python, SQL, Bash, JavaScript

**Ingestion and ETL** Scrapy, Playwright, Selenium, BeautifulSoup, schema validation, deduplication, incremental loading, data quality checks

**Data stores** PostgreSQL, MySQL, MongoDB, Redis

**Backend** Django, Flask, FastAPI, REST API design

**Infrastructure** Docker, Linux, Git, Jenkins, GitHub Actions, GCP, AWS

**Analysis and ML** Pandas, NumPy, scikit-learn, PyTorch, Hugging Face Transformers

**Currently building depth in** Airflow, dbt, Spark

### Open to

Data engineer, Python engineer and backend roles in the UK. I have the right to work here and do not need sponsorship.

[LinkedIn](https://www.linkedin.com/in/shah-hussain-03255a15b) · shahhussain2044@gmail.com
