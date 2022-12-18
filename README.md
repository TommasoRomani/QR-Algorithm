# QR-Algorithm

## Introduction
 The QR algorithm is a very important algorithm for the computation of eigenvalues, but in practice it computes the Schur decomposition of a given matrix.
 The basic algorithm idea is to calculate a series of product between the **R** and **Q** term of the QR decomposition.
 
 A great limitation of this algoritm is that it fills general sparse matrix and therefore it can only be applied to dense matrix, reducing the possible dimension of the problem

## Basic QR
Like we said earlier the first iteration of this algorith involved the use of the QR factorization, used for the first time by J. G. F. Francis wich noticed that earlier methods based on LR factorization were unstable.

We now describe this first approach analitically, first we notice that:
$$A_k = R_k Q_k = Q^*_kA_{k-1}Q_k$$


