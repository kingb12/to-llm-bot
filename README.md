# 

Running Zero-Shot `gpt-3.5-turbo` with **generated belief states**:

```bash
python run.py --cache_dir "/localscratch/bking2/.cache/huggingface" \
    --model_name "gpt-3.5-turbo" \
    --faiss_db "multiwoz-context-db.vec" \
    --num_examples 0 \
    -- dials_total 20 \
    --output "results_zs_gdb" \
    --run_name "zs_gdb" \
    --split "validation" \
    --use_zero_shot
```
