# Documentation preview for CGAL issues #9600 and #9681

Download and extract `cgal-api-fixes-docs.zip`, then open:

- `SMDS_3/group___pkg_s_m_d_s3_i_o_functions.html` for `read_MEDIT()`.
- `Arrangement_on_surface_2/class_c_g_a_l_1_1_arr__conic__traits__2_1_1_construct__curve__2.html` for the full-conic overloads.

Built from commit `f6095558` with CGAL's documentation configuration and Doxygen 1.18.0 on Windows. These are isolated package builds: references to other packages and bibliography entries are not fully resolved. CGAL's patched Doxygen and full documentation build remain the authority for release documentation.

This branch contains review material only. It is separate from the source pull request.

`cgal-5150-docs.zip` contains the Spatial_searching documentation from commit `f94b7a339f3`, clarifying that Fuzzy_sphere includes its boundary.

`cgal-8064-docs.zip` contains the Triangulation documentation from commit `b91f3d9540f`, describing finite-vertex stream output.

`cgal-5075-docs.zip` contains the manual from commit `5fbd7ae771d`, documenting `CGAL_ENABLE_EXPENSIVE_ASSERTIONS`. Open `Manual/configurationvariables.html`.

`cgal-2855-docs.zip` contains the Arrangement_on_surface_2 documentation from commit `f22de6ebdf9`, documenting the circular-segment traits bounding-box functor.

`cgal-8340-docs.zip` contains the SMDS_3 documentation for the counts by subdomain and surface-patch index. Refreshed from commit `2f7167f7` with the names `number_of_cells_in_subdomain()` and `number_of_facets_in_patch()`. It uses the same documentation configuration and Doxygen version described above.

`cgal-4319-docs.zip` contains the Number_types documentation for exact construction of MP_Float from built-in integral types.

`cgal-8260-docs.zip` contains the STL_Extension documentation for pointer overloads of Compact_container::s_iterator_to().

`cgal-7147-docs.zip` contains the Kernel_23 documentation for the non-degenerate triangle requirement of has_on() and point/triangle do_intersect().
