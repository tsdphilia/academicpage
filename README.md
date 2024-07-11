Jianbin Wang - Homepage

<h1 align="center">
</h1>
forked from RayeRen/acad-homepage.github.io

.author__avatar {
  display: table-cell;
  vertical-align: top;
  width: 75px;
  // set width only, for non-square avatars
  height: 75px;

  @include breakpoint($large) {
    display: block;
    width: auto;
    height: auto;
  }

  img {
    max-width: 175px;
    min-width: 75px;
    border-radius: 0%;//50%;

    @include breakpoint($large) {
      padding: 0px;
      border: 1px solid $border-color;
    }
  }
}
.greedy-nav{
  color:#fff
}
