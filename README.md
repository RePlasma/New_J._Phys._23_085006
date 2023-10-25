# Impact of the laser spatio-temporal shape on Breit–Wheeler pair production

Original authors: A Mercuri-Baron, M Grech, F Niel, A Grassi, M Lobet, A Di Piazza and C Riconda

Link to paper: https://iopscience.iop.org/article/10.1088/1367-2630/ac1975

Reproduced by: Óscar Amaro

Reproducing figures 1, 2, and 5.

__Notes__:

Evolution of energy moments of distribution. Normalization $\int f~d \gamma = 1$.

Vlasov-Fokker-Plank equation $d_t f = C[f] = \partial_\gamma [S f] + 0.5 \partial_{\gamma \gamma}[R f]$

Mean energy:

$$d_t \langle \gamma \rangle = \int ~\gamma ~d_t f ~d\gamma = \int \gamma \partial_\gamma [S f] + 0.5\gamma~ \partial_{\gamma \gamma}[R f]~d\gamma=$$

$$=(\gamma S f)| - \int S f d\gamma + 0.5(\gamma \partial_\gamma[R f])|-0.5 \int \partial_\gamma[R f] d\gamma=$$

$$= -\int S f d\gamma = -\langle S \rangle$$

Mean square energy:

$$d_t \langle \gamma^2 \rangle = \int \gamma^2 ~d_t f ~ d\gamma = \int \gamma^2 \partial_\gamma [S f] + 0.5\gamma^2~ \partial_{\gamma \gamma}[R f]~d\gamma =$$

$$=(\gamma^2 S f)| - 2\int \gamma ~S f d\gamma + 0.5(\gamma^2  \partial_\gamma[R f])|- \int \gamma~\partial_\gamma[R f] d\gamma=$$

$$=- 2\int \gamma ~S f d\gamma - (\gamma R f)| + \int R f d\gamma = -2 \langle \gamma S\rangle + \langle R \rangle$$

where $X| = X|_1^\infty$ and assuming $f(\gamma\rightarrow \infty) \rightarrow 0$
