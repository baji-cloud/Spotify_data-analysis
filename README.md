# Spotify_data-analysis
<img width="238" height="148" alt="spotify" src="https://github.com/user-attachments/assets/92c6501e-d4f3-4dc0-894a-cbc2b9e73b69" />

# 🎵 Spotify Data Analysis with Advanced SQL

A hands-on project analyzing a Spotify tracks dataset using **Level 1 to Level 3 SQL queries**, including **window functions**, **CTEs**, **conditional aggregation**, and **query optimization**.

## 🎯 Objective
- Practice real-world data analysis using SQL
- Explore music trends (streams, views, audio features)
- Optimize query performance

## 🛠️ Tools Used
- PostgreSQL (or MySQL/SQLite – specify yours)
- DBeaver / pgAdmin / VS Code

## 📊 Dataset Overview
- **Rows**: [e.g., 20,000 tracks]
- **Columns**: `track`, `artist`, `album`, `stream`, `views`, `likes`, `danceability`, `energy`, `liveness`, `licensed`, `official_video`, etc.
- **Source**: [Mention if from Kaggle/public source – or “simulated for learning”]

## 🔍 Key Insights
- Over **XX tracks** have >1B streams (e.g., “Blinding Lights”).
- Artists like **[Top Artist]** dominate total track count.
- **Spotify vs YouTube**: Some tracks perform better on Spotify despite YouTube being the main platform.

## 📚 Query Highlights
- ✅ **Level 1**: Basic filtering, grouping, counting  
- ✅ **Level 2**: Aggregations per album, top-N tracks  
- ✅ **Level 3**: Window functions (`DENSE_RANK`), CTEs, ratio analysis  
- ⚡ **Optimization**: Used `EXPLAIN ANALYZE` to evaluate performance

## 📂 Files
- `level1_basic_analysis.sql`
- `level2_intermediate.sql`
- `level3_advanced_windowing.sql`
- `query_optimization.sql`

> 💡 **Learning in public!** Open to feedback on query efficiency & best practices.
