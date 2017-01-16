# Logistic Regression

- Loss Fuctions Used
  - Hinge Loss
  - Log Likelikehood Loss

- Momentums Studied
 - Polyak
 - Nestrov

- Requirements
  - Please ensure that exec.sh has executable privileges
    - chmod +x exec.sh
    
- Instructions
  - exec.sh can be executed with the following options:
     ▪	arg1: Type of loss (log, hinge)
     ▪	arg2: Type of momentum (polyak, nag or none)
  - The below will execute with default parameters– log loss with polyak (classical) momentum
    ▪	./exec.sh

  - Below are the various combinations that the code can be executed in:
    ▪	./exec.sh log
    ▪	./exec hinge
    ▪	./exec log polyak
    ▪	./exec hinge polyak
    ▪	./exec log nag
    ▪	./exec hinge nag
    ▪	./exec log none
    ▪	./exec hinge none
  
  - Caution:
    ▪	Please note that not providing an argument would let the code execute with default parameters– if no parameters are provided at all,
    log likelihood loss with Polyak momentum is set. If the wrong loss parameter is passed, again log likelihood is set. If a valid loss parameter is passed and no or incorrect momentum is passed, Polyak momentum is set.
