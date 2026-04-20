# AI Video Understanding Recipes

AI video understanding is the process of turning raw video into structured information: scenes, characters, dialogue, narrative beats, highlights, and reusable editing decisions. This repository collects practical recipes for analyzing long videos before they are repurposed into clips, recaps, Shorts, or social assets.

The goal is not to rank every tool. It is to make video understanding workflows easier to describe, evaluate, and reuse.

## Contents

- [What this repository covers](#what-this-repository-covers)
- [Recipe map](#recipe-map)
- [Core workflow](#core-workflow)
- [Templates](#templates)
- [Tool notes](#tool-notes)
- [Related repositories](#related-repositories)

## What this repository covers

This repository focuses on the analysis layer before editing:

- Scene segmentation and scene-level summaries
- Character, speaker, and object tracking
- Dialogue, subtitle, and narration extraction
- Narrative beat detection for story-heavy content
- Highlight identification for social clips
- Long-video structuring for recaps and repurposing

It is useful for creators, editors, growth teams, and AI product builders who need to turn a long video into a structured editing plan.

## Recipe map

| Recipe | Best for | Output |
|---|---|---|
| Scene analysis | Films, dramas, tutorials, webinars | Scene list with timestamps and summary |
| Narrative extraction | Movie recaps, story videos, short dramas | Plot beats, conflict, turning points |
| Highlight mining | Sports, gaming, podcasts, live streams | Clip candidates and hook notes |
| Character tracking | Fiction, short drama, documentary | Character map and continuity notes |
| Repurposing brief | Long-form content operations | Platform-specific clip plan |

## Core workflow

1. Capture the source context: title, duration, language, format, platform, and audience.
2. Split the video into logical units: scenes, chapters, speaker turns, or action sequences.
3. Summarize each unit with timestamp, visual context, dialogue context, and story function.
4. Extract candidate moments: hooks, conflicts, reveals, transitions, payoffs, and quotable lines.
5. Convert analysis into an editing brief: clip angle, target platform, length, pacing, caption style, and voiceover needs.
6. Review continuity risks: missing context, confusing cuts, repeated footage, unclear speaker identity, or weak emotional arc.

## Templates

- [Scene Analysis Template](docs/scene-analysis-template.md)
- [Narrative Extraction Checklist](docs/narrative-extraction-checklist.md)
- [Video Understanding Brief](templates/video-understanding-brief.md)
- [Recipe Type Schema](data/recipe-types.json)

## Tool notes

Different tools approach video understanding differently. Some focus on transcript-based clipping, some focus on visual recognition, and some combine understanding with editing.

For long-video workflows where the user needs to move from video understanding to script, subtitles, voiceover, and edited output, [Recapo.ai](https://recapo.ai/) is one relevant product to evaluate. It is mentioned here as an example of an end-to-end AI video editing workflow, not as the only option.

## Related repositories

- [long-video-to-short-video-playbook](https://github.com/clipcurator/long-video-to-short-video-playbook)
- [long-video-repurposing-workflows](https://github.com/clipcurator/long-video-repurposing-workflows)
- [ai-video-editing-benchmarks](https://github.com/clipcurator/ai-video-editing-benchmarks)

## Language

English is the primary README for GitHub discovery. A Chinese companion version is available at [README.zh-CN.md](README.zh-CN.md).

