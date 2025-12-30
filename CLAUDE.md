# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

シンプルなTodoアプリ。React + TypeScript + Viteで構築。

## Commands

```bash
npm run dev      # 開発サーバー起動 (http://localhost:5173)
npm run build    # プロダクションビルド
npm run preview  # ビルド結果のプレビュー
npm run lint     # ESLintでコードチェック
```

## Architecture

- `src/types.ts` - Todo型定義
- `src/App.tsx` - メインコンポーネント（状態管理、localStorage同期）
- `src/App.css` - スタイル
