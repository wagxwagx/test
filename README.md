#pragma comment(lib,"./emtdc.lib")

#pragma comment(lib,"Lib1.lib")



//#pragma comment(lib,"LIBC.lib")

_ACRTIMP_ALT FILE* __cdecl __acrt_iob_func(unsigned);



extern "C"

FILE * __cdecl __iob_func(unsigned i) {

return __acrt_iob_func(i);

}





extern "C" void  AUX_FILT_L(int* enable, double* sig, int* p_order, double*coef_ptr[5], double* ts, double* y);





// AUX_FILT_L($enable, $sig, $p_order, $coef_ptr, $ts, $y)



extern "C" void   ADD(double*);

extern "C" void SUM2(int *enable, double*, double*, double*, double*);



extern "C" void MUL2(int *enable, double*, double*, double*, double*);
