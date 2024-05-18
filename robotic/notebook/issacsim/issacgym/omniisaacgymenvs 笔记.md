
# python环境设置
```bash
alias PYTHON_PATH=~/.local/share/ov/pkg/isaac_sim-2023.1.1/python.sh
```

# 启动Balance测试
```bash
PYTHON_PATH scripts/rlgames_train.py task=Cartpole
 checkpoint=runs/Balance/nn/Balance.pth test=True num_envs=1 
```

# 如何添加新的仿真任务

* yaml文件
* 每个任务有2个配置文件: `cfg/task` 和 `cfg/train`
* 