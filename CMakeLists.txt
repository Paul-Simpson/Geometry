set(srcs
    "Geometry.cpp"
    )

idf_component_register(SRCS "${srcs}"
                    INCLUDE_DIRS "."
                    REQUIRES BasicLinearAlgebra
                    )
