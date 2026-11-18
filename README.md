# Export-Import Agent Skills

Reusable educational skills for AI agents / Skill pembelajaran reusable untuk AI agent.

## Skills

| Skill | English | Bahasa Indonesia |
| --- | --- | --- |
| `trade-orientation` | Concepts, trade scenarios and reflection | Konsep, skenario perdagangan, dan refleksi |
| `trade-research` | Evidence-based market research planning | Perencanaan riset pasar berbasis bukti |
| `portfolio-coach` | Organizing work and rubric-based feedback | Penataan karya dan umpan balik berbasis rubrik |

## Installation / Instalasi

Portal & documentation: https://lensetek-int.github.io/export-import-agent-skills/

Requires Node.js 22.20+ and npm. Run from the **project where you want the skills installed**:

Memerlukan Node.js 22.20+ dan npm. Jalankan dari **proyek tujuan instalasi**:

```bash
npx skills add https://github.com/lensetek-int/export-import-agent-skills
```

Select skills and an available agent when prompted. Default installation is project-local; `-g` selects global installation. Review the source before installing; running `npx` downloads and executes the CLI.

Pilih skill dan agent yang tersedia. Secara default instalasi berlaku untuk proyek; `-g` untuk instalasi global. Tinjau sumber sebelum instalasi; `npx` mengunduh dan menjalankan CLI.

## Compatibility / Kompatibilitas

Skills use portable `SKILL.md` instructions and do not depend on a particular model or vendor tool. The [`skills` CLI](https://github.com/vercel-labs/skills) supports many agents, including OpenCode, Claude Code and Codex. Support for any particular agent, including Antigravity or Freebuff, depends on its current skill-loading behavior and has not been verified here. For unsupported agents, consult their documentation and load the instructions manually if supported.

Skill menggunakan instruksi `SKILL.md` portabel dan tidak bergantung pada model atau alat vendor tertentu. CLI mendukung banyak agent, tetapi kompatibilitas tiap agent, termasuk Antigravity dan Freebuff, belum diverifikasi di proyek ini. Untuk agent yang tidak didukung, periksa dokumentasinya dan muat instruksi secara manual jika memungkinkan.

## Try it / Contoh penggunaan

1. **Orientation:** “Use trade-orientation to teach me how a coffee business might approach its first export. Speak Indonesian.”
2. **Research:** “Use trade-research to make an evidence checklist for coffee exports. Separate assumptions from verified facts.”
3. **Portfolio:** “Use portfolio-coach to review my reflection using this rubric. Do not publish it.”

1. **Orientasi:** “Gunakan trade-orientation untuk mengajarkan ekspor pertama usaha kopi dalam Bahasa Indonesia.”
2. **Riset:** “Gunakan trade-research untuk membuat daftar bukti riset ekspor kopi dan pisahkan asumsi dari fakta terverifikasi.”
3. **Portofolio:** “Gunakan portfolio-coach untuk meninjau refleksi saya berdasarkan rubrik ini. Jangan publikasikan.”

## Safety / Keamanan

Never paste API keys, passwords, or confidential data into prompts. Review agent permissions and ask permission before sharing documents with external services. AI output is educational, can be wrong, and does not replace professional customs or legal advice.

Jangan masukkan API key, kata sandi, atau data rahasia ke prompt. Tinjau izin agent dan minta persetujuan sebelum mengirim dokumen ke layanan eksternal. Hasil AI dapat keliru dan bukan pengganti nasihat profesional.

## Verify / Verifikasi

Run `npx skills list` from the target project and restart the agent if needed. Ask it to use one of the skills above. If it cannot find the skill, consult the agent's documentation and verify its installation path.

Jalankan `npx skills list` dari proyek tujuan dan mulai ulang agent jika diperlukan. Minta agent menggunakan salah satu skill. Jika tidak ditemukan, periksa dokumentasi dan lokasi instalasi agent.
