# 🧠 NeuroSync — AI Agent in a Jupyter Notebook (no API key)

A free AI agent that runs on your own computer. No account or API key needed.

**Tools:** calculator · date/time · notes memory · Wikipedia lookup · web page reader
**Brain:** a small open-source model (Qwen2.5-0.5B) for general chat. Set `USE_LLM = False` in the notebook to skip it and start instantly.

## Run it
```bash
git clone https://github.com/<your-username>/NeuroSync.git
cd NeuroSync
pip install -r requirements.txt
jupyter notebook NeuroSync_Agent.ipynb
```
Then choose **Run All** and chat in the last cell.

No setup on your PC? Open the notebook in [Google Colab](https://colab.research.google.com) (File → Upload / Open from GitHub) and run all cells.

## Example messages
- `calculate (1234*56)/7 + sqrt(144)`
- `what time is it?`
- `remember: submit report on Friday` then `what do you remember?`
- `who is Albert Einstein`
- `read https://example.com`

Notes are saved locally in `neurosync_notes.json` (git-ignored).
