GuardTalkOS: symlink trunk-14096387 -> grapheneos.

trunk_staging sets RELEASE_KERNEL_DIR to .../trunk-14096387; the pinned
kernel prebuilt in this tree is .../grapheneos. Same pattern as caiman
(caimito-kernels/6.1/trunk-14096387) and laguna (6.6/trunk-14072179).
Reversible: rm the symlink.
