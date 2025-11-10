## Personal Expense Assistant — Multimodal Agent

## Overview

This project demonstrates a **full-stack multimodal AI agent** with **frontend**, **backend**, and **RAG (Retrieval-Augmented Generation)** capabilities using **Google’s Agent Development Kit (ADK)** and **Gemini 2.5**.

The application helps users manage their personal expenses by:

* Extracting data from uploaded **receipt images**
* Storing structured data in **Firestore**
* Performing both **metadata-based** and **semantic (vector)** searches
* Managing receipt image uploads in **Google Cloud Storage (GCS)**

It showcases an **end-to-end AI integration** with cloud backend, vector search, and multimodal understanding.

---

## What We Are Doing

* Setting up a Google Cloud project with:

  * **Firestore** (for data and vector embeddings)
  * **GCS Bucket** (for storing images)
  * **Composite and vector indexes** (for search)
* Building a **Python agent** using **ADK + Gemini 2.5**
* Creating tools for:

  * `store_receipt_data()` → store extracted receipt details
  * `search_receipts_by_metadata_filter()` → query by date/amount
  * `search_relevant_receipts_by_natural_language_query()` → vector search
  * `get_receipt_data_by_image_id()` → fetch stored receipt info
* Running the app through:

  * ADK **web interface** (`uv run adk web`)
  * or **API server** for backend testing

---

## Tech Stack

* **Language:** Python 3.12
* **Framework:** Google ADK (Agent Development Kit)
* **Model:** Gemini 2.5
* **Database:** Firestore
* **Storage:** Google Cloud Storage
* **Frontend:** ADK Web UI
* **Environment Management:** uv
---

## 🎥 Video Walkthrough

👉 **Add your walkthrough video link here:**
[Watch the Demo Video](#)
