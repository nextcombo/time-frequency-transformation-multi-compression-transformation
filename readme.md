# Time-Frequency Transformation: Multi-Compression Transformation

The sparsity representation of non-stationary signals with harmonic and pulse components is a prominent issue in the field of data science. The recommendations from basic tracking [32] and matching pursuit [33] help to distinguish between two components in the signal. However, harmonic components and pulse components cannot be appropriately matched simultaneously. Inspired by RM and unidirectional compression techniques, this paper proposes a "divide and conquer" time-frequency multi-compression transform (TFMST) strategy that can accurately describe both harmonic and class-pulse components in the signal while preserving the ability to restore the original signal either entirely or partially. The remainder of this paper is organized as follows.
MATLAB main code: clear; \nN =2501; \nfs=2501; \nt = (0:N-1)/fs; \nw=0:2*pi*fs/(N-2):2*pi*1250*fs/(N-2); \nx = hermite_m(2501,63); \nx2=x'.*exp(1i*2*pi*(650)*((1:2501)/2501)); \n​\n[Ts,tfr1] = TFMST_Y(real(x2'),155); \n​\nfigure; imagesc(abs(tfr1)); axis xy; \n​\nfigure; imagesc(abs(Ts)); axis xy; MATLAB simulation results

## Images

![(Time-Frequency Transformation)Time-Frequency Multi-Compression Transformation [with MATLAB code]](01.jpg)
![(Time-Frequency Transformation)Time-Frequency Multi-Compression Transformation [with MATLAB code]](02.jpg)
![(Time-Frequency Transformation)Time-Frequency Multi-Compression Transformation [with MATLAB code]](03.jpg)
![(Time-Frequency Transformation)Time-Frequency Multi-Compression Transformation [with MATLAB code]](04.jpg)
![(Time-Frequency Transformation)Time-Frequency Multi-Compression Transformation [with MATLAB code]](05.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
