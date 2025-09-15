Task 3
机器人需要接收并解析明确的指令才能行动。本关旨在考察你的基础编程和数据处理能力。

C++ 方向
指令日志分析器:

任务: 编写一个C++程序，它接收一个命令行参数作为日志文件的路径，读取该文件，统计并打印出每种指令各自执行了多少次。

测试 请在你的项目中创建 commands.log 文件，并使用以下内容作为测试数据：


MOVE
SHOOT
MOVE
SCAN
SHOOT
MOVE
SHOOT
测试要求: 你的 test.sh 脚本应能编译程序，并像这样运行它：./your_program_name commands.log

Python 方向
机器人状态配置:

任务: 编写一个Python程序，它接收一个命令行参数作为配置文件的路径，读取该JSON文件，并将其中的信息格式化地打印出来。

测试 : 请在你的项目中创建 config.json 文件，并使用以下内容作为测试数据：


{
  "robot_name": "sentry_01",
  "health": 100,
  "ammo": 250,
  "enabled_modules": ["vision", "can_bus"]
}
测试要求: 你的 test.sh 脚本应能像这样运行它：python3 your_script_name.py config.json