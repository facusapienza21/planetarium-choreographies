# planetarium-choreographies

Finding choreographies of planets requires to minimize the action functional 

A = \frac{2\pi}{T} \sum_{t=1}^T [ \sum_{i=1}^N \frac{m_i}{2} \| \dot{z}_i (2\pi t / T) \|^2 +
	\sum_{i < j} \frac{m_i m_j}{ \| z_i(2\pi / T) - z_j(2\pi t/T) \| }  ]

where the trajectory of each planet i is given by

x_i (t) = a_0 + \sum_{k=1}^K [ a_k \cos( k (t + \varphi_i) ) + b_k \sin( k (t + \varphi_i) ) ]
y_i (t) = c_0 + \sum_{k=1}^K [ c_k \cos( k (t + \varphi_i) ) + d_k \sin( k (t + \varphi_i) ) ]
