# Julia_Lectures

Notes for teaching UG and G courses on signal processing and inversion where I start introducing Julia.

function wave_1(f0,dt,alpha,N)
    t = collect(0:1:N-1)*dt
    w = sin.(2*pi*t*f0).*exp.(-alpha*t)
    return t,w
end

function wave_2(f0,dt,alpha,N)
    t = collect(0:1:N-1)*dt
    w = sin.(2*pi*t*f0).*exp.(-alpha*t)
    return t,w
end

