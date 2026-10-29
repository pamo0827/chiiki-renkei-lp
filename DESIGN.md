---
version: alpha
name: 地域連携くん 紹介ページ
description: 訪問看護・在宅ケアの地域連携担当者向けサービスの紹介ページ。デジタル庁デザインシステム（DADS）の色・文字・余白に沿う。
colors:
  primary: "#0031D8"
  primary-hover: "#0017C1"
  primary-dark: "#000071"
  primary-tint: "#E8F1FE"
  neutral: "#FFFFFF"
  surface-tint: "#F8F8FB"
  text: "#1A1A1C"
  text-sub: "#626264"
  border: "#CCCCCC"
  focus: "#FFD43D"
typography:
  display:
    fontFamily: Noto Sans JP
    fontSize: 44px
    fontWeight: 700
    lineHeight: 1.35
  h2:
    fontFamily: Noto Sans JP
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.5
  h3:
    fontFamily: Noto Sans JP
    fontSize: 18px
    fontWeight: 700
    lineHeight: 1.7
  body-md:
    fontFamily: Noto Sans JP
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.7
rounded:
  sm: 4px
  md: 8px
  lg: 16px
spacing:
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    height: 48px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.neutral}"
  button-secondary:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
  section-tint:
    backgroundColor: "{colors.surface-tint}"
    textColor: "{colors.text}"
  card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.text}"
    rounded: "{rounded.md}"
  feature-icon:
    backgroundColor: "{colors.primary-tint}"
    textColor: "{colors.primary}"
  heading:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary-dark}"
  caption:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.text-sub}"
  divider:
    backgroundColor: "{colors.border}"
  focus-ring:
    backgroundColor: "{colors.focus}"
    textColor: "{colors.text}"
---

## Overview
介護・福祉の事業所の担当者が読む、落ち着いた紹介ページ。白地に青1色で組み、強調は太字と青だけで行う。

## Colors
主色は DADS の blue-900。見出しは blue-1200、薄い背景は blue-50。文字は本文 #1A1A1C、補足 #626264 で、どちらも白地で 4.5:1 以上。フォーカスは DADS の決まりどおり黄（yellow-300）と黒の二重線にし、変えない。

## Typography
Noto Sans JP の Regular と Bold だけを使う。本文は 16px・行の高さ 1.7。スマートフォンでは見出しを 30px / 24px に下げる。

## Layout
最大幅 1120px、左右の余白 16px。セクションの上下は 64px（スマートフォンは 40px）。

## Shapes
角丸は 4px（タグ）・8px（ボタン・カード）・16px（料金の箱・画面のイメージ）。

## Components
ボタンは高さ 48px 以上。カードは白地に 1px の線で、色を塗った箱は使わない。

## Do's and Don'ts
- 料金は検討中のため「仮」を必ず付ける。
- 実績や導入数など、確かめていない数字は書かない。
