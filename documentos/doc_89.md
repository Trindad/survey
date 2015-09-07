## Resumo

We propose a rate-adaptive transmission scheme using variable-rate forward error correction (FEC) codes with a fixed signal constellation and a fixed symbol rate, quantifying how achievable bit rates vary with distance in a long-haul fiber system. The FEC scheme uses serially concatenated Reed-Solomon (RS) codes with hard-decision decoding, using shortening and puncturing to vary the code rate. An inner repetition code with soft combining provides further rate variation. While suboptimal, repetition coding allows operation at very low signal-to-noise ratio (SNR) with minimal increase in complexity. A rate adaptation algorithm uses the SNR or the FEC decoder input bit-error ratio (BER) estimated by a receiver to determine the combination of RS-RS and repetition codes that maximizes the information bit rate while satisfying a target FEC decoder output BER and providing a specified SNR margin. This FEC scheme is combined here with single-carrier polarization-multiplexed quadrature phase-shift keying (PM-QPSK) and digital coherent detection, achieving 100-Gbit/s peak information bit rate in a nominal 50-GHz channel bandwidth. We simulate variable-rate single-channel transmission through a long-haul system incorporating numerous optical switches, evaluating the impact of fiber nonlinearity and bandwidth narrowing. With zero SNR margin, achievable information bit rates vary from 100 Gbit/s at 2000 km, to about 60 Gbit/s at 3000 km, to about 35 Gbit/s at 4000 km. Compared to an ideal coding scheme achieving information-theoretic limits on an AWGN channel, the proposed coding scheme exhibits a performance gap ranging from about 5.9 dB at 2000 km to about 7.5 dB at 5000 km. Much of the increase in the gap arises from the inefficiency of the repetition coding used beyond 3280 km. Rate-adaptive transmission can extend reach when regeneration sites are not available, helping networks adapt to changing traffic demands. It is likely to become more important with the continued evo- - lution toward optically switched mesh networks, which make signal quality more variable.


## Anotações
