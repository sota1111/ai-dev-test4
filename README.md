# TimeQuest Ops

## Overview
TimeQuest Ops は、GPS と AI を使って、現在地から街歩きクエストを生成する AI エージェントプラットフォームです。

## Demo

🌐 **GitHub Pages**: https://sota1111.github.io/ai-dev-test4/

## Concept
街歩きを、AI が冒険に変える。
ユーザーは、歩く・探す・撮る・答えるだけで、普段の街に隠れた歴史や社会的な気づきを発見できます。

## Problem
- 地域の歴史・文化資源が見過ごされやすい
- 観光が有名スポットに偏りやすい
- 普段の街を歴史・防災・バリアフリーなどの視点で見る機会が少ない

## Solution
- GPS で現在地を取得
- Gemini が周辺スポットや街の特徴をもとにクエストを生成
- ユーザーが写真や回答を投稿
- AI がフィードバックし、次のクエストを提案
- 利用データをもとにクエストを継続改善

## Key Features
- 現在地ベースのクエスト生成
- 写真を使ったクエスト達成判定
- AI によるヒント・解説・フィードバック
- 今日の街歩きストーリー生成
- 運営者向けのクエスト改善ダッシュボード
- GitHub / CI/CD / Cloud Run による継続配信

## AI Agents
- Quest Planner Agent: 現在地や周辺情報からクエストを生成
- Quest Guide Agent: 写真や回答を見てヒントや解説を返す
- Quest QA Agent: 安全性・事実性・表現をチェック
- Quest Ops Agent: 利用データをもとに改善案を提案

## Tech Stack
- Frontend: Flutter / Web
- Backend: Cloud Run
- AI: Gemini API, ADK, Gemini Vision
- Database: Firebase Firestore
- Storage: Cloud Storage
- DevOps: GitHub, GitHub Actions, Cloud Build, Cloud Run Deploy

## MVP Scope
- 現在地取得
- 周辺スポット取得
- AI によるクエスト生成
- 写真アップロード
- AI フィードバック
- クエスト完了カード生成
- 簡易 Ops ダッシュボード

## Hackathon Fit
TimeQuest Ops は、AI エージェントがクエストを生成・案内・評価・改善する体験を提供します。
さらに、クエスト定義やプロンプトを GitHub で管理し、CI/CD によって Cloud Run へ継続配信することで、DevOps × AI Agent の文脈に適合します。
