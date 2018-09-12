#ifdef MICRO_THC
#define IN_D_TORCH_ON_PIN      6
#else
#define IN_D_TORCH_ON_PIN      10
#endif
#ifdef MICRO_THC
#define IN_D_ARC_GOOD_PIN 	8
#else
#define IN_D_ARC_GOOD_PIN 	12
#endif
#ifdef MICRO_THC
#define OUT_D_ARC_GOOD 		3
#define OUT_D_TORCH_UP 		2
#define OUT_D_TORCH_DOWN	4
#else
#define OUT_D_ARC_GOOD 		2
#define OUT_D_TORCH_UP 		3
#define OUT_D_TORCH_DOWN	4
#endif


