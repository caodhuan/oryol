fips_begin_app(GPUParticles windowed)
    fips_vs_warning_level(3)
    fips_files(GPUParticles.cc)
    oryol_shader(shaders.glsl)
    fips_deps(Gfx Assets Dbg)
    oryol_add_web_sample(GPUParticles "Fully GPU driven 3D particles" "emscripten" GPUParticles.jpg "GPUParticles/GPUParticles.cc")
fips_end_app()
