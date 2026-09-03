<h1 align="center">Zhu Lei · 朱磊</h1>

<p align="center">
  LLM serving · RAG · agent systems<br/>
  Wuxi, China
</p>

<p align="center">
  <a href="https://github.com/langgenius/dify/commits?author=kabishou11"><img src="https://img.shields.io/badge/Dify-contributor-1a7f37" alt="Dify contributor" /></a>
  <a href="https://github.com/vllm-project/vllm/pull/55089"><img src="https://img.shields.io/badge/vLLM-bugfix%20PR-0969da" alt="vLLM PR" /></a>
  <a href="https://github.com/infiniflow/ragflow/pulls?q=is%3Apr+author%3Akabishou11"><img src="https://img.shields.io/badge/RAGFlow-bugfix%20PRs-0969da" alt="RAGFlow PRs" /></a>
  <a href="mailto:woicyou@gmail.com"><img src="https://img.shields.io/badge/gmail-woicyou%40gmail.com-555" alt="gmail" /></a>
  <a href="mailto:woicyou@qq.com"><img src="https://img.shields.io/badge/qq-woicyou%40qq.com-12B7F5" alt="qq email" /></a>
</p>

I run production LLM / RAG stacks and send **upstream bugfixes** — real reproductions, tests, and the smallest change that actually fixes the failure.

---

## Upstream

| Project | PR | What | Status |
|--------|-----|------|--------|
| [langgenius/dify](https://github.com/langgenius/dify) | [#41719](https://github.com/langgenius/dify/pull/41719) | Stringify object values before Monaco `createModel` (Start-node `json_object` crash) | **Merged** |
| [langgenius/dify](https://github.com/langgenius/dify) | [#41696](https://github.com/langgenius/dify/pull/41696) | Map plugin-daemon runtime-not-ready to retryable **503** (was 400 `invalid_param`) | Open |
| [langgenius/dify](https://github.com/langgenius/dify) | [#41708](https://github.com/langgenius/dify/pull/41708) | Skip invalid plugin-daemon list items so one bad plugin cannot take down Tools / Models | Open |
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | [#19206](https://github.com/infiniflow/ragflow/pull/19206) | Agent Retrieval compares embeddings by resolved model, not raw UUID vs composite `embd_id` | Open |
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | [#19208](https://github.com/infiniflow/ragflow/pull/19208) | Wiki MAP completeness sees just-extracted chunks (`kb_id` on resume rows) | Open |
| [vllm-project/vllm](https://github.com/vllm-project/vllm) | [#55089](https://github.com/vllm-project/vllm/pull/55089) | Preserve model text when `tool_choice` is `none` | Open |
| [HYGON-AI/vllm-plugin-das](https://github.com/HYGON-AI/vllm-plugin-das) | [#55](https://github.com/HYGON-AI/vllm-plugin-das/pull/55) | Default CustomAllreduce **off** on PCIe / no-XGMI (incl. TP=2) | Open |

Open PRs are waiting on maintainer review — not merged yet.

---

## Selected work

- **[dify-skills](https://github.com/kabishou11/dify-skills)** — executable ops skills for self-hosted Dify (console API, plugins, intranet installs)
- **[DocForge](https://github.com/kabishou11/DocForge)** — LLM document generation (Markdown / DOCX)
- **[voiceprint-asr-platform](https://github.com/kabishou11/voiceprint-asr-platform)** — speaker recognition + multi-speaker transcription

---

## Stack

`Python` `TypeScript` `vLLM` `Dify` `RAGFlow` `Milvus` `Docker`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kabishou11&show_icons=true&hide_title=true&count_private=true&theme=transparent&hide_border=true" alt="GitHub stats" height="140" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kabishou11&layout=compact&theme=transparent&hide_border=true" alt="Top languages" height="140" />
</p>
