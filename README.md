# Broadcasted_RandVars_withoutArrayofArray

Broadcasted random variables can be obtained from `@. rand.(Dist.(params), sample_size);`, however, the gotten data format is Array{Array{Float64, 1},K}, where `params` is K-tensor. In this notebook, we test the two (temporal) methods for generating data with Array{Float64, K+1} format.
