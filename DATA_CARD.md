# Data Card: ESG-LLM Manually Annotated Dataset

## Motivation
This dataset is created to support and validate large language model–based ESG (Environmental, Social, and Governance) scoring methods.  
Existing ESG rating systems often suffer from low transparency, poor reproducibility, and high subjectivity. By releasing a manually annotated ESG dataset with clearly defined scoring rules, this dataset aims to improve methodological transparency, enable model evaluation and comparison, and facilitate reproducible research in ESG-related natural language processing and financial economics.

## Data Source
All annotations are derived from publicly available Corporate Social Responsibility (CSR) reports disclosed by Chinese A-share listed companies.  
CSR reports are collected from official stock exchange platforms and company websites and are prepared according to widely adopted reporting standards such as GRI and related sustainability guidelines.  
No proprietary, confidential, or non-public information is included in this dataset.

## Annotation Scheme
- Annotation unit: firm–year ESG indicator evaluation with supporting textual evidence
- ESG dimensions: Environmental (E), Social (S), and Governance (G)
- Total number of indicators: 54
- Scoring values:
  - `1` — Concrete ESG actions accompanied by quantitative outcomes or measurable performance indicators
  - `0.5` — ESG actions disclosed without quantitative outcome evidence
  - `0` — No concrete ESG actions or outcomes disclosed
- The annotation scheme emphasizes both action implementation and outcome disclosure to reduce narrative bias and greenwashing risk.

## Annotation Process and Quality Control
- Annotators received standardized training and written annotation guidelines prior to formal labeling
- A pilot annotation phase was conducted to ensure consistency and clarify ambiguous cases
- A subset of samples was cross-checked by multiple annotators to assess labeling reliability
- Annotation workloads were controlled to mitigate fatigue-related bias

## Intended Use
This dataset is intended for:
- Academic research on ESG measurement and sustainability assessment
- Validation and benchmarking of large language model–based ESG scoring methods
- Instruction fine-tuning and evaluation in ESG-related NLP tasks

The dataset is **not intended for commercial use**, investment advisory services, or direct decision-making without further validation.

## Limitations
- ESG evaluation inherently involves subjective judgment, particularly in borderline cases
- The dataset focuses on Chinese listed firms and may not generalize directly to other institutional or regulatory contexts
- The annotation reflects reported disclosures and may not fully capture firms’ actual ESG performance

## Ethical Considerations
- The dataset contains no personal, sensitive, or private information
- All source documents are publicly available
- Annotations are conducted solely for research purposes and do not constitute investment advice or firm-level endorsements

