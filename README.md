# pigeon

Task queue for GPUs

## Vision

There will be times when you need to run a lot of tasks on the GPU and have to wait for current tasks to complete.
Other times the GPU is sitting idle and there are no tasks running on there.
Wouldn't it be great to have a queue that you can submit jobs to that will automatically schedule jobs for you?
This way you don't have to manually check the status of the GPU and manually start jobs when they are free.
You can also submit a batch of jobs at the same time and just wait for the result while you do something else.

This tool is envisioned to be the underlying scheduler for [labmate](https://github.com/tuzhucheng/labmate),
which is used for managing your own machine learning experiments.

**What's in a name?** Pigeons are known to be effective messengers. Pigeon is designed to be a messenger between you
and the GPU so you can worry less.
