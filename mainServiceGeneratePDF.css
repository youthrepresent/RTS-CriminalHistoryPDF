/*
  There is some strangeness in the way the PDF renderes elements. So, there is a
  level of ingenuity here. The rounded case containers are images, as the
  border-radius property wasn't an option.

  A note to any other developers who come along that might have questions...

  RTS Labs 6/5/2018
RTS LABS 08/14/2018 DMI updated @page.bottom-center to allow for page numbering.
*/


* {
  font-family: Helvetica, Arial, sans-serif;
  font-size: 12px;
}

@page {
  size: letter;
  margin: 80px 0 80px 0;

  @top-left {
    content: element(header-left);
  }
  @top-right {
    content: element(header-right);
  }
  @bottom-left {
    content: element(footer-left);
  }
  @bottom-right {
    content: element(footer-right);
  }
}

/* HEADER / FOOTER */
.header-left,
.header-right,
.footer-left {
  font-size: 11px;
  line-height: 16px;
  font-weight: bold;
}

.header-left {
  position: running(header-left);
  width: 450px;
  padding-left: 40px;
}

.header-left span,
.header-right span {
  display: block;
}

.header-right {
  position: running(header-right);
  display: inline-block;
  font-weight: bold;
  padding-right: 20px;
}

.footer-left {
  position: running(footer-left);
  display: block;
  padding-bottom: 15px;
  padding-left: 40px;
}
#pageNum:before {
      font-size: 80%;
       content: "Page " counter(page) " of " counter(pages);
 }
.footer-right {
  position: running(footer-right);
  text-align: right;
  padding-right: 40px;
  padding-bottom: 15px;
}

/* PAGE BANNERS */
.page-title {
  display: inline-block;
  position: relative;
  top: 35px;
  left: 30px;
  color: white;
  font-size: 18px;
}

.disclaimer {
  margin-top: 5px;
  margin-left: 15px;
  padding: 0 30px;
  width: 550px;
  font-size: 11px;
  line-height: 15px;
}

/* widely used styles */

.uppercase {
  text-transform: uppercase;
}

.fs-11px {
  font-size: 11px;
}

.align-to-top {
 vertical-align: top;
}

/* in some cases, <strong> tags carry additional styling */
.bold {
  font-weight: bold;
}

.gray-text {
  color: #4c4d4f;
}
.red-text {
  color: #ca383f;
}

.dsply-blk {
  display: block;
}
.dsply-ib {
  display: inline-block;
}


/* margins */
.mt-15px {
  margin-top: 15px;
}
.mt-25px {
  margin-top: 25px;
}
.ml-30px {
  margin-left: 30px;
}
.ml-40px {
  margin-left: 40px;
}
.ml-60px {
  margin-left: 60px;
}
.pl-60px {
  padding-left: 60px;
}
