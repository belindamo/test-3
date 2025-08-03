# Research project: test-3

This research project was created with [The Research Company](https://theresearchcompany.ai)

## Project Structure

- `paper_drafts/` - Draft versions of research papers
- `grant_proposals/` - Grant proposal documents  
- `bit_flip.jsonl` - Tracked assumption inversions (bit: problem, flip: solution)
- `experiment_proposals.jds` - Detailed experiment proposals with evaluation plans
- `experiments/` - Organized experiment folders
  - Each experiment contains: `plan.md`, `result.md`, `run/`, `analysis/`
- `related_work/` - Literature review notes and paper summaries
- `section_notes/` - Working notes for paper sections
- `data/` - Research data (max 2GB per file, use Git LFS for larger)
- `.github/workflows/` - Automated workflows including Claude AI assistant
- `CLAUDE.md` - AI research assistant instructions

## Getting Started

1. Start by documenting your bit flip hypothesis in `bit_flip.jsonl`
   - **Bit**: What is the current problem or assumption?
   - **Flip**: How are you challenging or solving this?
2. Create detailed experiment proposals in `experiment_proposals.jds`
3. Conduct literature review and add notes to `related_work/`
4. Plan and execute experiments in `experiments/`
5. Draft your paper in `paper_drafts/`

## Research Methodology

This project follows the CS197 research methodology. See `CLAUDE.md` for detailed guidance.
