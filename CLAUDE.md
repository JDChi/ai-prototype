# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

AI-assisted prototyping with mobile-first HTML/Tailwind prototypes.

## Code Style

- Use Tailwind CSS utility classes
- Mobile frame: max-width 414px
- Configure brand colors in Tailwind config
- Custom CSS only for animations

## Project Structure

Each project in separate folder under `projects/`:
```
projects/example/
projects/xxx-project/
```

## Project README

Each project folder must include a `README.md` file with:

- **Background** - Why create this prototype?
- **Design Goals** - What problems to solve?
- **Target Users** - Who is this for?
- **Key Features** - List main features
- **Design Highlights** - Special design elements

Example structure:
```markdown
# 项目名称

## 项目背景
（为什么要做这个原型）

## 设计目标
（想解决什么问题）

## 目标用户
（面向哪类用户）

## 主要功能
- 功能点 1
- 功能点 2
- ...

## 设计亮点
- 特色设计 1
- 特色设计 2

### Auto-update README
When adding or removing features, automatically update the "主要功能" (Key Features) section in the project's README.md. Keep other sections (Background, Goals, Users, Highlights) unchanged as they reflect original design intent.

## Commands

```bash
open projects/*/*.html  # View prototypes
git add && commit && push
```
