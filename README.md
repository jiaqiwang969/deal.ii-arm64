Dockerfile change to "FROM jiaqiknight/dealii:vscode-arm64"

Deal.ll tested on Apple m1 chip, allowing dockerfile to generate arm64, which can be run on vscode by ssh & container.
please ref to : https://github.com/dealii-courses/sissa-mhpc-lab-02

Or just run:
docker pull jiaqiknight/dealii:vscode-arm64

If you occur: fatal error:Killed signal terminated program cc1plus错误解决方法
That is because your docker is set with low RAM，enlarge it.



The test material is almost from https://github.com/dealii-courses/sissa-mhpc-theory-and-practice-of-fem

Thanks Luca-heltai! I learned a lot. His course is very intersting.
