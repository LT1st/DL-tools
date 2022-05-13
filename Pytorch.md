# 保存模型
torch.save(模型.module, '{}_retinanet_{}.pt'.format(parser.dataset, epoch_num))

# 环境测试
assert torch.__version__.split('.')[0] == '1'

print('CUDA available: {}'.format(torch.cuda.is_available()))

