# devf
Repository for devf.

Here is the code:

sub satan {
  use warnings;
  use strict;

  my $mensaje = shift;
  my $copia = $mensaje;
  $copia =~ s/[^e]*//gi;
  print "\n\tFrecuencia de 'e': ", length($copia), "\n";
  return reverse($mensaje);
}
