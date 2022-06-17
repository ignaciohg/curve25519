project('libcurve25519', 'c', 'cpp')

libcurve25519src = [
    'source/curve25519_mehdi.c',
    'source/curve25519_order.c',
    'source/curve25519_utils.c',
    'source/curve25519_dh.c',
    'source/ed25519_sign.c',
    'source/ed25519_verify.c',
    'source/sha512.c',
    'source/custom_blind.c',
]

libcurve25519 = library('libcurve25519', libcurve25519src)

libcurve25519_dep = declare_dependency(include_directories : ['include','source'],
  link_with :libcurve25519)

