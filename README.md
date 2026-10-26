# Awesome-Document-Extraction-API

## Top Document Extraction API Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Intelligent Document Processing, OCR & Structured Data Extraction*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Document Extraction APIs**. These tools convert unstructured documents (PDFs, scans, images, Office files) into structured, machine-readable data by combining OCR, layout analysis, table recognition, and AI-driven field extraction for invoices, receipts, contracts, forms, and identity documents.



**Examples** include Adobe PDF Extract API, AWS Textract, Google Cloud Document AI, Azure AI Document Intelligence, Rossum, Kofax TotalAgility, ABBYY FlexiCapture, Docparser, Hyperscience, and Nanonets OCR (the category leaders).



**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted document parsing, OCR pipelines, table extraction, and LLM-ready document conversion — ideal for developers, data teams, and enterprises building sovereign document intelligence without per-page API pricing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Adobe PDF Extract API](https://developer.adobe.com/document-services/apis/pdf-extract/)**  

  AI/ML-powered API that extracts content, structure, and renditions from PDFs into JSON, identifying paragraphs, lists, headings, tables, and figures with character bounding boxes; optional CSV/XLSX table output and PNG image extraction .



- **[AWS Textract](https://aws.amazon.com/textract/)**  

  Managed OCR and document analysis service with specialized APIs for forms, tables, invoices/receipts (AnalyzeExpense), identity documents (AnalyzeID), and lending documents; supports synchronous and asynchronous processing .



- **[Google Cloud Document AI](https://cloud.google.com/document-ai)**  

  Document processing platform with pre-trained and custom extractors, layout parser, form parser, and generative AI-powered derived fields for inferring values not explicitly written (e.g., currency codes, signature detection) .



- **[Azure AI Document Intelligence](https://azure.microsoft.com/en-us/products/ai-services/ai-document-intelligence)**  

  Cloud API for document extraction with pre-built models for invoices, receipts, IDs, and custom extraction via the Document Intelligence client library and REST API .



- **[Rossum](https://rossum.ai/)**  

  AI-native document automation platform with template-free extraction, 276+ language support, and SAP-certified integration for AP, order management, and logistics workflows .



- **[Kofax TotalAgility](https://www.kofax.com/products/totalagility)**  

  Integrated intelligent automation platform combining low-code process design, AI-driven document processing, RPA, and case management; available as Kofax-hosted or customer-hosted deployment .



- **[ABBYY FlexiCapture](https://www.abbyy.com/flexicapture/)**  

  Intelligent document processing and data capture platform for structured and semi-structured documents (invoices, forms, contracts), with FlexiLayout Studio for unstructured layouts and pre-trained invoice capture .



- **[Docparser](https://docparser.com/)**  

  Template-based document data extraction service for invoices, orders, bank statements, and reports; outputs to Excel, CSV, JSON, XML, Google Sheets, or via API and integrations .



- **[Hyperscience](https://hyperscience.com/)**  

  Intelligent automation platform with ML-based document extraction and human-in-the-loop review; available as SaaS on GCP/AWS with SOC 2 Type II attestation and optional Labor-as-a-Service .



- **[Nanonets OCR](https://nanonets.com/)**  

  AI document extraction platform with pre-built models for receipts, invoices, and IDs; supports PNG/JPEG/PDF uploads, field editing with model learning, and API integration .



## Open-Source GitHub Projects



- **[Docling](https://github.com/docling-project/docling)**  

  MIT-licensed IBM Research toolkit for parsing PDF, DOCX, PPTX, images, HTML, and more into structured JSON/Markdown; uses DocLayNet for layout analysis and TableFormer for table structure recognition, with native LangChain/LlamaIndex integration and efficient CPU execution .



- **[Unstructured](https://github.com/Unstructured-IO/unstructured)**  

  Open-source library for partitioning and extracting structured content from raw documents (PDF, HTML, Word, images); provides chunking by document elements, cleaning, and staging functions optimized for LLM/RAG pipelines (note: open-source version is for prototyping, not production-scale) .



- **[Apache Tika](https://github.com/apache/tika)**  

  Foundational content detection and extraction toolkit supporting 1,600+ file formats; the `tikara` Python wrapper provides JNI-based integration with streaming, language detection, MIME detection, and recursive document unpacking .



- **[Docext (Nanonets)](https://github.com/Nanonets/docext)**  

  On-premises, OCR-free unstructured data extraction and markdown conversion toolkit with benchmarking; positioned as an open-source alternative for document intelligence with 1,700+ GitHub stars .



- **[TWIX](https://github.com/ucbepic/TWIX)**  

  Open-source data extraction tool that reconstructs structured data from documents at scale by inferring shared visual templates across documents; suitable for high-volume, low-cost extraction pipelines .



- **[DocSlight](https://github.com/ComPDFKit/docslight)**  

  Open-source AI document parsing and extraction project from ComPDF (KDAN ecosystem); supports PDF, scans, images, and Office files with PaddleOCR/VLM OCR, layout analysis, field extraction with BBox traceability, and outputs Markdown/JSON/Text for RAG and IDP workflows .



- **[docket](https://pypi.org/project/docket-idp/)**  

  Local document AI pipeline with hybrid OCR (text layer → Tesseract → VLM), classification, and Pydantic-schema extraction; includes deterministic validation (IBAN, VAT, arithmetic), human-in-the-loop review queue, FastAPI REST API, and support for invoices, receipts, contracts, and CLM analysis .



- **[ocrguru](https://pypi.org/project/ocrguru/)**  

  Lightweight CLI wrapper around the Docling OCR pipeline; supports RapidOCR, EasyOCR, and Tesseract engines with output to Markdown, JSON (with coordinates), or hOCR; MIT-licensed and cross-platform .



- **[UniDocVerse](https://github.com/bommavj/unidocverse-service)**  

  Privacy-first multi-vertical document intelligence platform with LangGraph orchestration, ReAct agents, hybrid pgvector retrieval, and Docling-based ingestion; Apache 2.0 licensed with 91.4% classification accuracy reported .



- **[pyonb](https://github.com/SAFEHR-data/pyonb)**  

  Open-source Python SDK bundling multiple OCR tools (Marker, Sparrow, PaddleOCR) behind a unified forwarding API for automated document-to-text conversion; containerized services suitable for clinical and large-scale archival processing .



### Additional Strong Open-Source Options



- **PaddleOCR** — Multilingual OCR toolkit with layout analysis and table recognition; widely used as an extraction engine in larger pipelines.

- **Tesseract** — The classic open-source OCR engine; still the default fallback in many extraction stacks.

- **Marker** — Fast PDF-to-Markdown conversion with table and equation support, often paired with OCR engines.

- **MinerU** — Document extraction toolkit with layout and formula recognition for scientific PDFs.

- **olmOCR** — OCR-focused toolkit for converting PDFs to clean text for LLM training pipelines.



**Frameworks for building custom systems**: Combine **Docling** for structured document conversion, **Tesseract** or **PaddleOCR** for OCR, **docket** for schema-validated field extraction, **Unstructured** for RAG-ready chunking, and **DocSlight** for BBox-traceable field extraction in a fully self-hosted document intelligence pipeline.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Document extraction systems must comply with applicable data privacy regulations (GDPR, HIPAA, etc.) and industry-specific requirements.

- Self-hosted open-source solutions require proper security hardening, OCR quality validation, and infrastructure planning (CPU/GPU, storage, model management).

- Verify license terms for commercial use; some projects use AGPL or custom licenses that may require releasing derivative code if distributed.



---



**Made for developers, data engineers, document AI practitioners, and automation teams.**  

Let's make document extraction more open, accurate, and accessible.
