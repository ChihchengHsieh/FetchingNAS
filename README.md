# FetchingNAS
Use RL(ActorCritic) and Fetching method for Searching Neural Network Operations


#### The results show they use the same weight repetitively


Current Best Dag: [{'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': 1, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(0, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': None, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 3, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}, {'Retrieve_cell': 0, 'Operation': 14, 'BatchNorm': 4, 'Act_fn': None, 'Attn': 0, 'Return_cell': 2, 'Put': 0, 'Output': tensor(1, device='cuda:0')}]
