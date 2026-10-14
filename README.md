# Documentation preview for CGAL issues #9600 and #9681

Download and extract `cgal-api-fixes-docs.zip`, then open:

- `SMDS_3/group___pkg_s_m_d_s3_i_o_functions.html` for `read_MEDIT()`.
- `Arrangement_on_surface_2/class_c_g_a_l_1_1_arr__conic__traits__2_1_1_construct__curve__2.html` for the full-conic overloads.

Built from commit `f6095558` with CGAL's documentation configuration and Doxygen 1.18.0 on Windows. These are isolated package builds: references to other packages and bibliography entries are not fully resolved. CGAL's patched Doxygen and full documentation build remain the authority for release documentation.

This branch contains review material only. It is separate from the source pull request.

`cgal-8340-docs.zip` contains the SMDS_3 documentation for the missing counts by subdomain and surface-patch index. It uses the same documentation configuration and Doxygen version described above.

`cgal-4319-docs.zip` contains the Number_types documentation for exact construction of MP_Float from built-in integral types.

`cgal-8260-docs.zip` contains the STL_Extension documentation for pointer overloads of Compact_container::s_iterator_to().
