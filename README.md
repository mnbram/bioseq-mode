# bioseq-mode
An Emacs major mode for viewing and editing DNA and peptide sequences

bioseq-mode is a major mode for the Emacs family of text editors that assists with the viewing and editing of biological sequences. Currently, DNA and peptide/amino acid sequences are supported, but RNA support is planned for the future.

bioseq-mode incorporates syntax highlighting (coloration) of nucleotides and amino acid residues as well as a handful of functions for manipulating sequence data, such as translation and reverse complementation.

Many features require a special file format, but conversion to and from FASTA files is built in.

bioseq-mode is intended to be a lightweight editor for those who would like to do simple editing of sequence data in a text editor. There is no built-in support for external programs such as BLAST or Clustal. Testing has been performed solely on single-gene sequence data, so some functions might act incorrectly or inefficiently on whole-genome sequence data.

bioseq-mode is released into the public domain, so feel free to use it however you want and adapt it to your needs.

## Installation instructions

You must have some version of Emacs installed in order to use bioseq-mode. Versions of Emacs are available for nearly every platform imaginable. All testing has been performed on GNU Emacs, but XEmacs might work just fine.

In order to use bioseq-mode, the bioseq-mode.el file must be saved somewhere in the Emacs load path. Instructions for doing so on at least some Linux platforms are given in at the beginning of the file. For other platforms, search the web for information on installing Emacs major modes on the platform of your choice.

Once the bioseq-mode.el file is saved in the load path, it can be loaded on request by typing "M-x bioseq-mode" (where "M" is probably the Alt key on your keyboard), or you can set it to autoload for certain file types by adding a few lines to your .emacs file. Instructions for autoloading are given at the beginning of the bioseq-mode.el file.