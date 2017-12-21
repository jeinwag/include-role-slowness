Demonstrates a potential bug in Ansible 2.4.2.0 concerning the usage of include_role with loops.
Each consecutive tasks using include_role is considerably slower (tasks named run 1 - run 3) than the previous one though each task should take roughly the same amount of time.


