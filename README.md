## A Deep RL Approach to Self-Driving Vehicles

- Reinforcement learning, the paradigm where an entity acquires the ability to make informed choices through its interactions with the surrounding environment, has experienced a remarkable surge of interest and advancement within the past few years. Undeniably, it has emerged as one of the most prominent and captivating subjects in the realms of artificial intelligence and machine learning, captivating the attention of countless researchers. Notably, the ongoing progress in this field has shown an exponential rate of development, with numerous breakthroughs being achieved at an astonishing pace. Within the framework of reinforcement learning, an agent is endowed with the capacity to transform its actions and accumulated experiences into a valuable source of knowledge, ultimately facilitating the enhancement of its decision-making skills in future scenarios.


### Environment
- GYM framework


### Usage

python main.py --environment_name 'CarRacing-v0' --model_path '/your_train_path/' --train_mode True --test_mode False --epsilon_greedy True --render True --width 96 --height 96 --num_stack 4 --huber_loss_thresh 1 --dropout 0.2 --memory_size 10000 --batch_size 128 --max_num_episodes 500















 






