/*global angular */
(function (angular) {
    'use strict';
    angular.module('mainApp', ['countdownTimer'])
        .controller('bodyController', function ($scope) {
            $scope.dates = [
                'October 31, 2015',
                'November 26, 2015',
                'December 25, 2015',
                'February 14, 2016'
            ];
            $scope.countdowns = [
                'Weeks',
                'Days',
                'Hours',
                'Minutes',
                'Seconds',
                'Weeks | Days',
                'Days | Hours | Minutes | Seconds'
            ];
            
        });
        
}(angular));