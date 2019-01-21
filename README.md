SGLD_DDPG


To train DDPG without exploration:
python DDPG/trainner.py  --env {Gym Envirnment}

To train DDPG with action noise:
python DDPG/trainner.py  --env {Gym Envirnment} --action-noise --stddev {noise stddev} 

To train DDPG with parameter noise:
python DDPG/trainner.py  --env {Gym Envirnment} --parameter-noise --stddev {noise stddev}

To train DDPG with SGLD:
python DDPG/trainner.py  --env {Gym Envirnment} --SGLD-mode 2 --train-mode 1