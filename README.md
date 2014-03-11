OurCar
======

OurCar means "our car to success"

# 检出工程、运行
1. clone the main repository
  git clone https://github.com/mazhao/ourcar.git

2. initialize all the submodules
  cd ourcar
  git submodule init
  git submodule update

3. open workspace
open ourcar.xcworkspace

# 更新ourcar子摸快的方法

  # change to the submodule directory
  cd ourcar 

  # checkout desired branch
  git checkout master

  # update
  git pull

  # get back to your project root
  cd ..

  # now the submodules are in the state you want, so
  git commit -am "Pulled down update to submodule_dir"
