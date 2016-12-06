# -gulp
简介
只做一件时，操作文件，其他的让其他的库去做。
只有5个function

gulp.task(name.fn)  It registers the function with a name.You can optionally specify some dependencies if other tasks need to run first.

gulp.run(tasks……)   Runs all tasks with maximum concurrency

gulp.watch(glob,fn) Runs a function when a file that matches the glob changes.Included in core for simplicity

gulp.src(glob)      This returns a readable stream.Takes a file system glob (like grunt) and starts emitting files that match.This is piped to other streams

gulp.dest(folder)   This returns a writable stream.File objects piped to this are saved to the file system
