使用方法：
运行脚本
输入基础VLESS节点URL
依次输入IP列表（每行一个，空行结束）
依次输入端口列表（每行一个，空行结束）
依次输入属地/名称列表（每行一个，空行结束）
程序将生成所有可能组合的新节点并显示
这个脚本会保持原有节点的所有参数（如encryption、security、sni等）不变，只替换需要批量修改的部分。生成的节点会自动对属地/名称进行URL编码，确保特殊字符不会导致问题。