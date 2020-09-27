# lumen-artisan-make-job

移植Laravel的 `php artisan make:job` [快速创建任务]指令到Lumen

# Usage

在 **'app/commands/kernel.php'** 中注册指令：

```
protected $commands = [
	\AdamTyn\Lumen\Artisan\JobMakeCommand::class
];
```

# Upgrade
[2020-09-24] 指令支持 `--sync` 选项